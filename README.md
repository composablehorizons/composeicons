<p align="center">
  <a href="https://composeicons.com" target="_blank">
    <img src="./art/logo.svg">
  </a>
</p>

<p align="center">
  We've converted the Internet's most popular icon libraries to Jetpack Compose Image Vectors, so you'll never run out of icons to use in your Compose apps.
<p>

<p align="center">
  <a href="https://composeicons.com"><strong>Browse at ComposeIcons.com &rarr;</strong></a>
</p>

## Basic Usage

### For Designers

Head over to [composeicons.com](https://composeicons.com), find an icon you need an click on
the `Copy SVG` button. Then go to any design tool of your choice such as Figma and paste the icon (`⌘ + V`) in your project.

### For Developers

Head over to [composeicons.com](https://composeicons.com), find the icon you need and click the `Copy Compose` button. 
It will add the Jetpack Compose Image Vector to your clipboard. Then paste the vector into your project and use it.

Use it in your project using the `Image()` composable:

```kotlin
import Check // your new icon

Image(Check, contentDescription = null)
```

Alternatively, use the `Icon()` composable from [Composables Core](https://composablescore.com) that supports tinting:

```kotlin
import Check // your new icon

Icon(Check, contentDescription = null, tint = Color.Blue)
```

## Icon Libraries

Instead of adding individual icons to your project, you can add an all icons in a library instead. 

To add them to your project, visit the respective icon library section: 

- [Lucide Compose](icons-lucide/)

## License

Each icon has a license of the respective icon library. To view each license, find the icon library
at [ComposeIcons.com](https://composeicons.com)

## Contributing

We are currently accepting contributions in the form of bug reports and feature & icons requests, in the form of Github issues.
