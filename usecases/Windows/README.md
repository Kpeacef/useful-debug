Windows useful debug commands

| Useful commands | Reference |
| ---| --- |

Format pendrive (Write protected)
```
cmd
diskpart
list disk
select disk <X>
atrributes disk clear readonly
clean
create partition primary
format fs=fat32
```
