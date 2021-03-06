## 2.2
* **AndroidX support**  (issues [#23](https://github.com/GiampaoloGabba/Xamarin.Plugin.SharedTransitions/issues/23)
* Fix IOS "Failed to lookup the required marshalling information" (issue [#31](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/31))
* Fix Tabbed page inside MasterDetail (issue [#30](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/30))
* Fontsize transition for label in iOS
* Improve Flip background animation in iOS
* Improve transition in iOS removing occasional flickering  
* TransitionStack improvement using Weakdelegates

## 2.1
* **Shell support**  (issues [#16](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/16), [#17](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/17), [#18](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/18))
* Tabbed page support (issue [#13](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/13))
* Master Detail page support (issue [#21](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/21))
* Fix DataTemplate in ListView (issue [#14](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/14))
* Improved sample apps (more demos for MasterDetail, TabbedPage & Shell)
* Code improvement & refactoring for better performance & stability
* Xamarin.Forms 4.3+ is required


## 2.0.2
* Fix issue [#10](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/10) (crash in iOS with non-existant image)
* Fix issue [#11](https://github.com/Evolutionlab/Xamarin.Plugin.SharedTransitions/issues/11) (backward transition duration in iOS)
* Fix Android backward transition duration

## 2.0.1
* **BREAKING:** Properties renamed to: Transition.Name, Transition.Group and TransitionDuration 
* Full MVVM support with TransitionSelectedGroup
* New, improved Transition management under the hood (no more limitation to int number for transition names & groups, faster view lookup for transitions)
* New transition engine for ios (support for shape transitions, including boxview, images with different bounds, aspect ratios, ecc..)
* New sample app in full MVVM with listview, collectionview and normal transitions (including demostrations with PancakeView and FFImageLoading)
* Everything mostly rewritten fro the ground-up: better stability and functionality
* Improved code comments and error handling 
* Added useful notes in code to help contributors to make this plugin better!


## 1.1.0
* Update to .NETStandard 2
* Fixed transitions between images with different aspect ratios
* Enable transitions between layouts (frame, stacklayout, ecc..) *Note: BoxView in iOS is not currently supported in this version*
* Updated Xamarin.Forms version from 3.1 to 3.6 (#6) by **@jsuarezruiz**
* Added new BackgroundAnimations (Flip, SlideFromLeft, etc.) (#7) by **@jsuarezruiz**
* Updated README with a new sample reference (#8) by **@jsuarezruiz**


## 1.0.0
* First release
