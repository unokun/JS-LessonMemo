# DOM$BA`:n(B
## $B%$%Y%s%H%O%s%I%i(B
DOM$BMWAG$K(BEventListener$B$rDI2C$9$k!#(B
```javascript
       function event_alert(){
           alert("$B%\%?%s$,2!$5$l$^$7$?(B");
       }
       var button = document.getElementById("alert");
       button.addEventListener("click", event_alert, false);
```

### $B=hM}$NN.$l(B
* addEventListern$B$G%$%Y%s%H=hM}EPO?(B
* $B%f!<%6!<A`:n(B($B%^%&%9$G%\%?%s%/%j%C%/(B)
* click$B%$%Y%s%HH/@8(B
* addEventListener$B$GEPO?$7$?4X?t$,<B9T$5$l$k(B
* $B%"%i!<%H$,I=<($5$l$k(B

### $B%$%Y%s%H<oN`(B
* clock
* mouseover
* keydown
* load

## $B<B9T%?%$%_%s%0(B
DOM$BMWAG$,$G$-$F$$$J$$>l9g$K$O!"<B9T$G$-$J$$!#(B
$BFC$K!"(BHTML$BFI$_9~$_;~!#(B
$B"((B) HTML$B$H(BJavaScript$B$O%3!<%I$N>e$+$i=gHV$KC`<!<B9T$5$l$k!#(B

$B%$%Y%s%H=hM}$O!"(Bwindow.onload($BFI$_9~$_40N;(B)$B$N;~$KEPO?$9$k$N$,NI$$!#(B
```javascript
window.onload = function () {
   var button = document.getElementById('overwrite');
   button.addEventListener('click', text_overwrite, false);
}
```
$BL5L>4X?t$N@bL@$r$9$k!#(B
$B4X?tL>$r9M$($kI,MW$,$J$$(B($B=EJ#$r5$$K$9$kI,MW$,$J$$(B)

## $BMWAG$N:n@.!&DI2C(B
$BMWAG$NEPO?$O0J2<$N<j=g$G9T$&!#(B
* $BMWAG:n@.(B
* $BB0@-!"%F%-%9%HMWAG$r@_Dj(B
* $BMWAG$rDI2C(B($B;RMWAG!&7;DoMWAG$H$7$F(B)

## $B0lDj4V3V$G7+$jJV$7<B9T(B
$B%?%$%^!<$r;H$&$H2hLL$,<+F0E*$KJQ2=$9$k$N$G%W%m%0%i%`$i$7$/$J$k!#(B
* $B%?%$%^!<3+;O(B(setInterval)
* $B%?%$%^!<=*N;(B(clearInterval)

## $B2]Bj(B
HTML$BMWAG$NDI2CN}=,(B

## $B2]Bj(B($B=i5i(B)
* HTML$BB0@-JQ99(B
* window.onload$B$G%$%Y%s%HEPO?(B

## $B2]Bj(B($BCf5i(B)
* $B%?%$%^!<;HMQ(B
* $BJ8;zNsA`:n(B
$BNc30=hM}$H$7$F!"J8;zNs$r$9$Y$FI=<($7$?8e$N=hM}$b9M$($k!#(B

