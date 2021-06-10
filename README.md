# Task

This is the continuation of the lists of GitHub users wherein focuses on writing a simple direct messaging detail screen.

# Minimum Specification

The app must perform the following tasks:

1. From the user's list screen, tapping one of these will push the navigation to detail scene.
2. The user can virtually send/receive messages.
3. Upon sending, the sent message must bounce back as received bubble with its content echoed twice. (Please refer to image below)
   - Implement a dummy or mock post & response request.
   - The sent message must echo back after a second.
   - No API must be called from this point.
4. Support for both portrait and landscape.

# Minimum Screen Specification

![](resources/example-screenshot.png)

# Additional Optional Specification

- Preferrably usage of sent/received bubble asset pngs.
- You may consider incorporating extra features or improved design. (e.g animations, growing text view, persistence, unit tests)
- Consider the datastore of messages to be interchangeable, following set of protocols/blueprints and resume history (e.g of data sources such as In-Memory, Realm, SQLite, CoreData, Firebase or REST APIs)

# Guidance for Code Quality

### Modern Architecture

- Demonstrate your preferred architectural design patterns. (e.g MVC, MVVM, modular, testable, etc)

### Knowledge of Cocoa Touch

- Demonstrate high knowledge of UIKit. (e.g Storyboards, AutoLayout, ConstraintLayout, programmatically UIs, etc)

### Coding Standard

- Write high quality Swift code using standard best practice coding conventions. This includes naming methods and classes, using structs and classes as needed. (e.g. Raywenderlich Swift Style, Gitflow)

# Evaluation Criteria

Implementation of [Minimum Specification](#Minimum-Specification), clearly communicating decisions and best engineering practices (e.g complexity, refactorability and scalability).

Examinee will also be hearing back the assessment of code's strengths, weaknesses.

# Requirements

- Latest Xcode
- Latest Swift / Storyboard UI
- Cocoapods or iOS / Cocoa Touch frameworks

# Submission

- Please configure the project/workspace to be able to run simply `CMD + R` or `Product > Run`
- Commit the directory containing the app and your README.md in master branch
- Send it back to your recruitment officer as an attachment in `tar` format
