# Mobile Development Learning Labs

A collection of Android and mobile development exercises consolidated from separate repositories. Each project lives in its own directory under [`projects/`](projects/) and remains independently openable; there is no shared build configuration.

These are learning projects and focused samples, not production applications. Use the individual project READMEs to understand each exercise and its setup.

## Projects

### Android fundamentals and Jetpack

| Project | Learning focus |
| --- | --- |
| [`kotlin_intents`](projects/kotlin_intents/) | Android intents and app components |
| [`implicit_intents_kotlin`](projects/implicit_intents_kotlin/) | Implicit intents and Android action routing |
| [`droid_cafe`](projects/droid_cafe/) | Cafe-ordering UI and basic app interactions |
| [`age_in_minutes_calculator`](projects/age_in_minutes_calculator/) | Date handling and a small Android utility |
| [`recycler_view_kotlin`](projects/recycler_view_kotlin/) | Lists, adapters, and RecyclerView |
| [`fragments_kotlin`](projects/fragments_kotlin/) | Fragment-based Android UI |
| [`bottom_nav_view_kotlin`](projects/bottom_nav_view_kotlin/) | Bottom navigation and screen structure |
| [`viewpager_kotlin`](projects/viewpager_kotlin/) | Swipeable pages and ViewPager navigation |
| [`nav_drawer_kotlin`](projects/nav_drawer_kotlin/) | Navigation drawer patterns |
| [`countdown_timer_kotlin_flow`](projects/countdown_timer_kotlin_flow/) | Countdown state with Kotlin Flow |
| [`navigation_component_kotlin`](projects/navigation_component_kotlin/) | Jetpack Navigation Component |
| [`viewModel_viewModelFactory_kotlin`](projects/viewModel_viewModelFactory_kotlin/) | ViewModel and factory-based construction |
| [`roomDatabase_kotlin`](projects/roomDatabase_kotlin/) | Local persistence with Room |
| [`BasicCalculator_ConstraintLayout`](projects/BasicCalculator_ConstraintLayout/) | Calculator UI and ConstraintLayout |

### Platform integrations and app exercises

| Project | Learning focus |
| --- | --- |
| [`GoogleAdmob_BannerAds`](projects/GoogleAdmob_BannerAds/) | AdMob banner integration |
| [`GoogleAdmobInterstitialAds`](projects/GoogleAdmobInterstitialAds/) | AdMob interstitial integration |
| [`GoogleAdmobRewardedAds`](projects/GoogleAdmobRewardedAds/) | AdMob rewarded-ad integration |
| [`ChatApp`](projects/ChatApp/) | Android chat application exercise |
| [`design_task`](projects/design_task/) | Flutter UI design exercise |

## Open and run a project

- For Android projects, open that project's directory in Android Studio, sync its Gradle files, and run the app on an emulator or device.
- Open `design_task` with a Flutter-enabled IDE and use the setup instructions in its README.
- Some exercises use older Android Gradle Plugin and SDK versions. Android Studio may require compatible SDK components or a Gradle update.
- Use AdMob test ad units for development. Keep personal keys and signing files out of the repository.

## Repository structure

Each directory under `projects/` is a snapshot of one former repository. The original repositories were retained separately; their commit histories are not included in this combined repository. No blanket license has been added; check each project for its own license and attribution.
