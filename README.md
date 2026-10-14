# How to Add Chip Items Dynamically in Blazor Chips Component?

## Overview

This sample demonstrates how to add chip items dynamically to the Syncfusion [Blazor Chips](https://www.syncfusion.com/blazor-components/blazor-chips) component. The application accepts text from the user and adds it to an item collection when the Add Chip button is selected. Each collection entry is immediately displayed as a removable chip, providing a simple way to manage user-entered tags or values.

## Key Features

- Uses the Syncfusion Blazor `SfChip` component to display dynamically generated chip items.
- Captures user-entered text for each chip through the `SfTextBox` component.
- Provides an Add Chip action through the `SfButton` component.
- Handles the button click using the `onToggleClick` method.
- Adds each entered value as a `Chip` object and stores it in `ChipItemCollection`.
- Renders the collection dynamically using `ChipItems` and individual `ChipItem` elements.
- Assigns the entered value to the `Text` and `Value` properties of each chip.
- Allows users to remove rendered chips by setting `EnableDelete="true"`.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

### Visual Studio 2022

1. Clone or download this repository.
2. Open the solution file:

   `AddingChipItems.sln`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `AddingChipItems`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the local application URL displayed by Visual Studio after launch.
8. Enter a value in the **Enter the chip text** field and select the **Add Chip** button. Verify that a new chip containing the entered value appears below the button with an option to delete it.

### Visual Studio Code

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory:

```bash
cd add-chips-dynamically-Blazor
```

5. Restore the NuGet packages:

```bash
dotnet restore
```

6. Run the project:

```bash
dotnet run
```

7. Open the local URL displayed in the terminal after the application starts.
8. Enter a value in the **Enter the chip text** field and select the **Add Chip** button. Verify that a new chip containing the entered value appears below the button with an option to delete it.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Chips getting started documentation](https://blazor.syncfusion.com/documentation/chip/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.