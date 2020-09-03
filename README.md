# androiddnsfix

androiddnsfix is a hack around the issues in https://github.com/golang/go/issues/8877

Credit to https://gist.github.com/cs8425/107e01a0652f1f1f6e033b5b68364b5e

Import it with

```golang
import _ "github.com/mtibben/androiddnsfix"
```

Any binary built with GOOS=android will have the fix applied
