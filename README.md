```javascript
import { Me, Coding } from "sergio-marquina";
  
const me = Me();

me.get("coding", (req, res) => {
  res.send(Coding.from(me).currentLanguages()); /* ["JavaScript, "Golang" ]*/
})

me.listen(80, () => console.log("Ready to code!"));
```

<div align="center">
<img src="https://cdn0.iconfinder.com/data/icons/flat-round-system/512/archlinux-512.png" height="175" width="175" style="margin: 10px">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Antu_org.kde.plasma.kicker.svg/1200px-Antu_org.kde.plasma.kicker.svg.png" height="175" width="175" style="margin: 10px">
<br>
<br>

[![Generic badge](https://img.shields.io/badge/distribution-arch-cyan.svg)](https://archlinux.org/)
[![Generic badge](https://img.shields.io/badge/desktop-plasma-darkblue.svg)](https://kde.org/plasma-desktop/)
<br>
</div>
