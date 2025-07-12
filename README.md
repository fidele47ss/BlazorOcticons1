# BlazorOcticons: Customizable GitHub Octicons for Your Blazor Apps 🎨

![GitHub Release](https://img.shields.io/github/v/release/fidele47ss/BlazorOcticons1?style=flat-square)

[![Download Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-blue?style=flat&logo=github)](https://github.com/fidele47ss/BlazorOcticons1/releases)

## Overview

BlazorOcticons is a library designed to bring GitHub's Octicons to your Blazor applications. This library offers a collection of customizable `.razor` components that make it easy to integrate icons into your projects. Whether you're building a dashboard, a personal blog, or a complex web application, BlazorOcticons provides the tools you need to enhance your user interface with minimal effort.

## Features

- **Easy Integration**: Quickly add Octicons to your Blazor app.
- **Customizable**: Adjust sizes, colors, and styles to fit your design.
- **Performance Optimized**: Built with efficiency in mind to ensure fast loading times.
- **Rich Icon Set**: Access a wide range of icons for various use cases.
- **Active Development**: Regular updates and community support.

## Installation

To get started with BlazorOcticons, you can install the package via NuGet. Run the following command in your terminal:

```bash
dotnet add package BlazorOcticons
```

After installation, you can start using the components in your Blazor application.

## Usage

### Basic Example

To use an Octicon in your Blazor component, simply include the desired icon in your markup. For example, to add a "star" icon:

```razor
<OcticonStar Size="24" Color="black" />
```

### Customization

You can customize the size and color of each icon. Here’s how you can change the size and color:

```razor
<OcticonHeart Size="32" Color="red" />
```

### List of Available Icons

BlazorOcticons includes a variety of icons. Here’s a brief list of some commonly used icons:

- `OcticonAlert`
- `OcticonCheck`
- `OcticonComment`
- `OcticonEye`
- `OcticonFork`
- `OcticonStar`

### Example Component

Here’s a simple example of a component that uses multiple Octicons:

```razor
@page "/icons"

<h3>My Icon Collection</h3>

<OcticonStar Size="24" Color="gold" />
<OcticonFork Size="24" Color="blue" />
<OcticonComment Size="24" Color="green" />
```

## Advanced Usage

### Custom SVG Icons

If you need to use custom SVG icons, you can create your own components by following this structure:

1. Create a new `.razor` file.
2. Use the `<svg>` tag to define your icon.
3. Make it customizable by accepting parameters for size and color.

### Example of Custom SVG Component

```razor
@code {
    [Parameter]
    public int Size { get; set; } = 24;

    [Parameter]
    public string Color { get; set; } = "black";
}

<svg width="@Size" height="@Size" fill="@Color" xmlns="http://www.w3.org/2000/svg">
    <!-- Your SVG path here -->
</svg>
```

## Community and Support

We welcome contributions from the community. If you have suggestions, bug reports, or feature requests, please open an issue on GitHub. 

### Contributing

To contribute to BlazorOcticons, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## Documentation

For detailed documentation, visit the [Documentation Section](https://github.com/fidele47ss/BlazorOcticons1/releases). Here you can find guides, API references, and more examples to help you get the most out of BlazorOcticons.

## Release Notes

To stay updated with the latest features and fixes, check the [Releases](https://github.com/fidele47ss/BlazorOcticons1/releases) section. Here, you can find the latest versions and download them directly.

[![Check Releases](https://img.shields.io/badge/Check%20Releases-Click%20Here-blue?style=flat&logo=github)](https://github.com/fidele47ss/BlazorOcticons1/releases)

## License

BlazorOcticons is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Topics

This repository covers the following topics:

- Blazor
- Blazor Components
- Components Library
- C#
- C# Source Generator
- .NET
- Icons
- Icons Pack
- Icon Set
- Octicons
- Razor
- Razor Components

## Contact

For questions or feedback, please reach out through GitHub issues or directly via email at [your-email@example.com].

## Acknowledgments

Thank you to the GitHub team for creating Octicons and for their ongoing support of open-source projects. 

## Final Notes

Explore the icons and customize them to fit your needs. Happy coding!