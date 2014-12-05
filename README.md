IMTheme
=======

Easy to implement universal app theme written in swift
=======

##How to use:<br/>
1. Place IMTheme.swift into your project<br/>
2. In your AppDelegate in the ```applicationDidFinishLaunchingWithOptions``` function, place the following code: IMTheme().setupTheme(primary: UIColor.blueColor(), secondary: UIColor.orangeColor())
3. Change the primary and secondary colors to whatever you desire
4. In IMTheme.swift, customize which objects need which color (primary or secondary) in the setupTheme function:
```Swift
        customizeLabel(color: primary)
        customizeNavBar(color: primary)
        customizeTabBar(color: secondary)
        customizeSwitch(color: secondary)
        customizeSearchBar(bar: primary, tint: secondary)
        customizeActivityIndicator(color: secondary)
        customizeButton(color: primary)
        customizeSegmentControl(primary: primary, secondary: secondary)
        customizeSlider(primary: primary, secondary: secondary)
        customizePageControl(primary: primary, secondary: secondary)
        customizeStepper(color: primary)
        customizeProgressView(primary: primary, secondary: secondary)
```
##Requirements

*	Xcode 6
*	iOS 7.0+

##Examples

![Refresher: preview default](https://raw.githubusercontent.com/jcavar/refresher/master/previews/anim_default.gif)

##Credits

IMTheme is created by [Ian MacCallum](https://twitter.com/imac239) and inspired by [MAThemeKit](https://github.com/mamaral/MAThemeKit) written in Objective-C.