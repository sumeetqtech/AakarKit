# AakarKit

**AakarKit** is a Jetpack Compose UI toolkit for Android, offering advanced components, responsive layouts, and seamless theming to simplify complex design. Build scalable, modern apps with pre-built, customizable elements like grids, forms, and animations—all inspired by the art of structure and elegance.

## Features

- **Advanced UI Components**: Forms, grids, accordions, expandable cards, and more.
- **Responsive Layouts**: Adaptive designs for various screen sizes and orientations.
- **Seamless Theming**: Light/dark mode support and customizable themes.
- **Built-in Animations**: Enhance user experience with smooth transitions and interactive gestures.
- **Modular Architecture**: Plug-and-play components for flexible integration.
- **Accessibility & Localization**: Optimized for screen readers and multi-language support.

## Installation

Add AakarKit to your project by including it in your `build.gradle`:

```groovy
dependencies {
    implementation "com.sumeetpanchal.aakarkit:aakarkit:1.0.0"
}
```

Ensure you have Maven Central repository included:

```groovy
repositories {
    mavenCentral()
}
```

## Usage

### Applying AakarKit Theme

Wrap your app with the `AakarKitTheme` to apply consistent styling.

```kotlin
import com.sumeetpanchal.aakarkit.theme.AakarKitTheme

@Composable
fun MyApp() {
    AakarKitTheme {
        // Your app content
    }
}
```

### Using a Toolkit Button

```kotlin
import com.sumeetpanchal.aakarkit.components.ToolkitButton

@Composable
fun SampleScreen() {
    ToolkitButton(
        text = "Click Me",
        onClick = { /* Handle Click */ }
    )
}
```

### Adding a Responsive Grid

```kotlin
import com.sumeetpanchal.aakarkit.components.ResponsiveGrid

@Composable
fun GridScreen() {
    val items = listOf("Item 1", "Item 2", "Item 3", "Item 4")
    ResponsiveGrid(items = items)
}
```

## Documentation

Comprehensive documentation is available [here](https://github.com/sumeetpanchal/aakarkit/docs).

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

## Contact

- **Author**: Sumeet Panchal
- **Email**: sumeetqtech@gmail.com
- **GitHub**: [sumeetpanchal](https://github.com/sumeetpanchal)
