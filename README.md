<div align="center">

## One\-line code to disable right click \(IE 5\.0\+\)


</div>

### Description

This code uses a miniumum amount of code to disable right click.
 
### More Info
 
The user has to right click.

It is useless against any browser that is not IE 5.0+, basically that.

It just disables the context menu.

The code is only IE 5.0+ compatible.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[a person, a thing, a being](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/a-person-a-thing-a-being.md)
**Level**          |Beginner
**User Rating**    |4.0 (20 globes from 5 users)
**Compatibility**  |
**Category**       |[Security](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/security__2-74.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/a-person-a-thing-a-being-one-line-code-to-disable-right-click-ie-5-0__2-2917/archive/master.zip)





### Source Code

```
<script>
document.oncontextmenu=new Function("return false")
</script>
```

