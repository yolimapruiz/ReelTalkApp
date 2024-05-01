# ReelTalkApp Demo

A mobile application dedicated to Movie and TV show enthusiasts who want to be part of a fun community.

#### Features
- Launch Screen
- Onboarding Flow
- Genre Selection
- Movie Selection View.
- TV Show Selection View.
- Guideline Agreement

#### Architecture Pattern
The selected architecture is MVVM. It aligns with SwiftUI's principles of declarative, reactive, and composable UI development.
   MVVM is effective for managing asynchronous operations, such as fetching data from APIs or performing background tasks. ViewModel components can handle data retrieval and transformation asynchronously, ensuring smooth interaction and responsiveness in the user interface.

![MVVM](https://github.com/yolimapruiz/ReelTalkApp/assets/125906928/2621ed2d-c151-4272-8f03-1d2027ae10e1)

   It also supports several aspects of the SOLID principles, particularly in terms of separation of concerns, extensibility, modularity, and dependency management. By leveraging MVVM, you can create SwiftUI applications that are easier to maintain, test, and evolve over time, aligning with the fundamental principles of good software design encapsulated in SOLID.
   
#### Style
About the Style guide:
Yoy have access to all the custome fonts stablished on the figma design on a swift file named ThemeFont. Anytime you want to customize a font use: .font(ThemeFont.{desired font}).

Same thing with the colors. Refere to ThemeColor t find all the colors in the desing and use "ThemeColor.[desired color]" as a color object to modify any color

![Mobile Style Guide](https://github.com/yolimapruiz/ReelTalkApp/assets/125906928/e56f113c-9333-401a-9562-0062a8e9c269)
