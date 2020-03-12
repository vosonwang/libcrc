# libcrc


源于 https://github.com/tbrandon/mbserver/blob/master/crc.go

|   修改者   |  时间    |
| ---- | ---- |
|   voson wang   |   2020-3-12   |



### 修改1
line 42

原先
```go
func crcModbus(data []byte) (crc uint16)
```
修改后
```go
func CRCModbus(data []byte) (crc uint16)
```

### 修改2

line 67 

原先
```go
c := uint16(i)
```

修改后

```go
c := i
```
