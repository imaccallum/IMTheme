IMTheme
=======

Easy to implement universal app theme written in swift

=======
How to use:
1. Place IMTheme.swift into your project
2. In your AppDelegate in the applicationDidFinishLaunchingWithOptions function, place the following code: IMTheme().setupTheme(primary: UIColor.blueColor(), secondary: UIColor.orangeColor())
3. Change the primary and secondary colors to whatever you desire
4. In IMTheme.swift, customize which objects need which color (primary or secondary) in the setupTheme function
