# UITapGestureRecognizer strange behavior

When instantiating `UITapGestureRecognizer` with custom targets (of non-`UIViewController` type) I have issues in recording the gesture tap.
It works only when the custom class is a property of the UIVIewController that embeds the button, see second button below.

![image](https://api.monosnap.com/rpc/file/download?id=NRjcYr6ULc6HRaeRz2JRfNmtEyhBc4)
