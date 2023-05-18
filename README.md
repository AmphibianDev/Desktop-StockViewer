# StockViewer: Your Real-Time Stock Market Companion

Always stay in sync with the financial markets using StockViewer, a convenient tool that floats live stock prices from Yahoo's API on the top of your screen. It's designed to keep critical market data at your fingertips without the constant need to visit a website. 

## Key Features

- **Always-on Display:** The application floats over windows but stays hidden during gaming sessions for minimal disturbance. 
- **Customizable Experience:** Personalize your stock portfolio by adding or removing stocks as you see fit. The options don't end there - dive in and explore more.
- **Multi-monitor Support:** Got multiple screens? No problem. StockViewer has you covered.

## Getting Started

1. Download the latest .exe version from the Releases section and run it.
2. Locate and right-click the blue StockViewer icon in your System Tray to access the settings or to exit the program.
3. After making any changes in the Settings, remember to click “Ok” for them to take effect.

## Building from Source

For those interested in compiling the code:

1. Open "StockViewer.sln" in Visual Studio.
2. Navigate to Tools -> NuGet Package Manager -> Package Manager Console.
3. Execute the following command in the console: `dotnet publish -c Release`.
4. Your compiled .exe file will be located at "StockViewer\bin\Release\net5.0-windows\win-x64\publish".

If you download .zip source file, you may need to unblock it if you want to debug or run the application in Visual Studio.

1. Right-click the downloaded .zip source file.
2. Choose Properties from the context menu.
3. Look for the 'Unblock' checkbox in the bottom right corner and deselect it.
4. Unzip the file.

With StockViewer, you're always one glance away from your financial interests. Start using it today!