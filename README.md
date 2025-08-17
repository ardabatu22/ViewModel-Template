# ViewModel-Template

This template saves time by automatically generating a `ViewModel` file with proper naming and boilerplate code.

---

## 🚀 Features
- Creates a `YourModuleNameViewModel.swift` file automatically
- Adds `@MainActor` and `ObservableObject` for SwiftUI compatibility
- Project name is dynamic (`___FILEHEADER___`), no hardcoded name
- Custom template icon included (orange VM logo)

---

## 📦 Installation

Clone this repo into your Xcode Templates folder:

```bash
git clone https://github.com/ardabatu22/ViewModel-Template.git \
~/Library/Developer/Xcode/Templates/ViewModel-Template
````

Your folder structure should look like this:

```
~/Library/Developer/Xcode/Templates/ViewModel-Template/
└── ViewModel.xctemplate/
    ├── TemplateInfo.plist
    ├── ___FILEBASENAME___.swift
    ├── TemplateIcon.png
    └── TemplateIcon@2x.png
```

---

## 🛠 Usage

1. Open **Xcode**
2. Go to **File > New > File…**
3. In the left panel, select **ViewModel-Template > ViewModel**
4. Enter your module name, e.g. `Login`
5. Xcode generates `LoginViewModel.swift`:

```swift
import Foundation

@MainActor
final class LoginViewModel: ObservableObject {
    init() {}
}
```

---


## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

