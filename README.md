# Japfa Database Document

```SQL
select m.menudesc,m.menugroup, m.notes, t.*, t.rowid 
from Mt_Menubyrole t 
join Mt_Menu m on t.menuid = m.menuid
where t.username in ('luong.nguyenthi') and t.apps like'%Pr%' and t.warehouseid ='RA'; --phân quyền thông tin Warehouse
```
