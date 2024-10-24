# mwg.blazor.components.bs5

A Blazor library consisting of Bootstrap 5 Blazor components. This is a work in progress, and it currently includes a `TabSet` and a `PageHeader` component.

## Installation

To start using the library in your Blazor project, install the package from NuGet:

```bash
dotnet add package mwg.blazor.components.bs5
```

## Usage

After installing the package, reference the library's stylesheet in your `index.html` or `app.razor` file:

```html
<link rel="stylesheet" href="_content/mwg.blazor.components.bs5/css/styles.css" />
```

## Components

### TabSet

The `TabSet` component allows you to create a tabbed interface. Here's an example of how to use it:

```razor
<mwg.blazor.components.bs5.TabSet>
    <mwg.blazor.components.bs5.Tab Title="tab1">
        <h1>Tab 1</h1>
    </mwg.blazor.components.bs5.Tab>
    <mwg.blazor.components.bs5.Tab Title="tab2">
        <h1>Tab 2</h1>
    </mwg.blazor.components.bs5.Tab>
</mwg.blazor.components.bs5.TabSet>
```

### PageHeader

The `PageHeader` component is designed for displaying page titles and additional actions or links. Here's how to use it:

```razor
<mwg.blazor.components.bs5.PageHeader Title="Bedrijven">
    <a href="bedrijf/create">Create New</a>
</mwg.blazor.components.bs5.PageHeader>
```

## Contributing

This library is a work in progress, and contributions are welcome! If you'd like to add more components or report issues, please feel free to open a pull request or issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
