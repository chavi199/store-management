# Store management

A .NET store application for customers, products, orders, sales, and a cashier screen. The solution is split into a business layer, two data implementations, and a WinForms UI.

One data project keeps records in memory. The other stores them as XML. The UI talks to the business layer, not to the files directly.

## Stack

- C# and .NET 8
- WinForms
- XML for the file-based data project

## Run

Open `DotNet2025_8430_6589/DotNet2025_8430_6589.sln` in Visual Studio and start the `UI` project.

## Layout

```text
BL/          business logic
DalFacade/   data contracts
DalList/     in-memory data
DalXml/      XML data
UI/          cashier, customers, products, orders, and sales screens
```

Build output and Visual Studio cache folders are ignored.
