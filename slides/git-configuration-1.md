##  git configuration

auto.autocrlf

```
$ git config --global core.autocrlf <true | input | false>
```

* true:   convert into LF when commit; convert into CRLF when checkout.
* input:  convert into LF when commit; do nothing when checkout.
* false:  do nothing when commit; do nothing when checkout.

__<font color='#F70'>If you're on a Windows machine, set it to ```true``` -- this converts LF endings into CRLF when you check out code.</font>__

```
$ git config --global core.safecrlf <true | false | warn>
```

* true:   reject commit if both have LF and CRLF
* false:  accept commit if both have LF and CRLF
* warn:   show warning if both have LF and CRLF
