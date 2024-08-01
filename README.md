
# How to add chip items dynamically in Blazor Chips component?

This sample explains about how to add chip items dynamically in Blazor Chips component.

## Prerequisites

* Visual Studio 2022

## How to run the project

* Checkout this repository in your local disk.
* Open the solution file using the Visual Studio 2022 / Visual Studio Code.
* Restore the NuGet packages by rebuilding the solution.
* Run the project.

# Add Chip Dynamically in Blazor

This repository shows how to add chips dynamically in Blazor. 

```Razor
<SfChip EnableDelete="true">
    <ChipItems>
        @foreach (Chip item in ChipItemCollection)
        {
            <ChipItem Text="@item.Text" Value="@item.Value"></ChipItem>
        }
    </ChipItems>
</SfChip>
```