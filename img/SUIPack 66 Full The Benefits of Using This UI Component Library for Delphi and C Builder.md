# SUIPack 66 Full: The Ultimate UI Component Library for Delphi and C++ Builder
 
If you are looking for a powerful and easy-to-use UI component library for Delphi and C++ Builder, look no further than SUIPack 66 Full. SUIPack 66 Full is a collection of more than 100 UI components that can help you create stunning and modern applications with minimal coding. Whether you need buttons, menus, toolbars, tabs, grids, charts, calendars, dialogs, or any other UI element, SUIPack 66 Full has you covered.
 
SUIPack 66 Full supports all versions of Delphi and C++ Builder from XE2 to 10.4 Sydney, and works seamlessly with VCL and FMX frameworks. You can choose from 15 predefined themes or customize your own theme with the built-in theme editor. You can also use the SUIForm component to apply skinning to your entire application with just one line of code.
 
**Download File ——— [https://t.co/oXJ3EgXDN9](https://t.co/oXJ3EgXDN9)**


 
Some of the features of SUIPack 66 Full include:
 
- High performance and low memory usage
- Support for high DPI and multi-monitor environments
- Support for touch and gesture input
- Support for alpha blending and transparency
- Support for PNG images and icons
- Support for right-to-left languages
- Support for Unicode and internationalization
- Support for drag-and-drop and clipboard operations
- Support for data binding and validation
- Support for printing and exporting
- Support for design-time and run-time customization
- And much more...

To download SUIPack 66 Full, visit the official website at [https://www.sunisoft.com/suipack/](https://www.sunisoft.com/suipack/). You can also find documentation, samples, tutorials, and support on the website. SUIPack 66 Full comes with a 30-day trial period and a 60-day money-back guarantee. Don't miss this opportunity to take your Delphi and C++ Builder applications to the next level with SUIPack 66 Full.
  
In this article, we will show you how to use some of the UI components from SUIPack 66 Full in your Delphi and C++ Builder projects. We will use the SUIButton, SUIPopupMenu, SUIToolBar, SUITabControl, and SUIGrid components to create a simple file explorer application. You can download the source code and the executable file from the link below.
 
SUIPack 66 Full download,  SUIPack 66 Full crack,  SUIPack 66 Full license key,  SUIPack 66 Full review,  SUIPack 66 Full tutorial,  SUIPack 66 Full components,  SUIPack 66 Full demo,  SUIPack 66 Full free trial,  SUIPack 66 Full price,  SUIPack 66 Full discount,  SUIPack 66 Full alternative,  SUIPack 66 Full vs VCLSkin,  SUIPack 66 Full vs AlphaControls,  SUIPack 66 Full vs DevExpress VCL,  SUIPack 66 Full vs TMS Component Pack,  SUIPack 66 Full for Delphi,  SUIPack 66 Full for C++ Builder,  SUIPack 66 Full for RAD Studio,  SUIPack 66 Full for Windows,  SUIPack 66 Full for Linux,  SUIPack 66 Full for macOS,  SUIPack 66 Full for Android,  SUIPack 66 Full for iOS,  SUIPack 66 Full skins,  SUIPack 66 Full themes,  SUIPack 66 Full customization,  SUIPack 66 Full documentation,  SUIPack 66 Full support,  SUIPack 66 Full forum,  SUIPack 66 Full blog,  How to install SUIPack 66 Full,  How to use SUIPack 66 Full,  How to update SUIPack 66 Full,  How to uninstall SUIPack 66 Full,  How to activate SUIPack 66 Full,  How to create a UI with SUIPack 66 Full,  How to design a UI with SUIPack 66 Full,  How to code a UI with SUIPack 66 Full,  How to debug a UI with SUIPack 66 Full,  How to test a UI with SUIPack 66 Full,  How to optimize a UI with SUIPack 66 Full,  How to deploy a UI with SUIPack 66 Full,  Benefits of using SUIPack 66 Full,  Features of using SUIPack 66 Full,  Drawbacks of using SUIPack 66 Full,  Tips and tricks for using SUIPack 66 Full,  Best practices for using SUIPack 66 Full,  Examples of using SUIPack 66 Full,  Case studies of using SUIPack 66 Full,  FAQs about using SUIPack 66 Full
 
## Creating the Project
 
To create the project, follow these steps:

1. Open Delphi or C++ Builder and create a new VCL or FMX application.
2. Save the project as FileExplorer.dproj and the main form as MainForm.pas.
3. Add the SUIPack package to your project by choosing Project -> Options -> Packages -> Runtime Packages and adding SUIPack\_Dxx.bpl to the list, where xx is your Delphi or C++ Builder version.
4. Drop a SUIForm component from the SUIPack palette onto the main form and set its Align property to alClient.
5. Drop a SUIToolBar component from the SUIPack palette onto the SUIForm and set its Align property to alTop.
6. Drop a SUITabControl component from the SUIPack palette onto the SUIForm and set its Align property to alClient.
7. Add two tabs to the SUITabControl by right-clicking on it and choosing Add Tab. Name the first tab Local and the second tab Remote.
8. Drop a SUIGrid component from the SUIPack palette onto each tab of the SUITabControl and set their Align properties to alClient.
9. Drop a SUIButton component from the SUIPack palette onto the SUIToolBar and set its Caption property to Connect.
10. Drop a SUIPopupMenu component from the SUIPack palette onto the main form and add some menu items to it by right-clicking on it and choosing Items Editor. Name the menu items Open, Copy, Paste, Delete, and Properties.

You should have something like this:
 ![Screenshot of the project](https://i.imgur.com/6y7g8ZT.png) 
## Configuring the Components
 
To configure the components, follow these steps:

1. Select the SUIForm component and choose a theme from the ThemeName property. For this example, we will use Office2016White.
2. Select each SUIGrid component and set their Options properties to [goFixedVertLine, goFixedHorzLine, goVertLine, goHorzLine, goColSizing]. This will enable grid lines and column resizing.
3. Select each SUIGrid component and set their FixedCols properties to 0. This will remove the fixed column on the left.
4. Select each SUIGrid component and add four columns by right-clicking on them and choosing Columns Editor. Name the columns Name, Size, Type, and Date Modified. Set their Width properties to 200, 100, 100, and 150 respectively.
5. Select each SUIGrid component and set their RowCount properties to 2. This will add an empty row for data.
6. Select each SUIGrid component and set their DefaultRowHeight properties to 24. This will increase the row height.
7. Select each SUIGrid component and set their OnDrawCell events to GridDrawCell. This will allow us to customize the cell appearance.
8. Select each SUIGrid component and set their OnDblClick events to GridDblClick. This will allow us to handle double-click events on cells.
9. Select each SUIGrid component and set their OnMouseDown events to GridMouseDown. This will allow us to handle mouse-down events on cells.
10. Select each SUIGrid component and set their PopupMenu properties to SUIPopupMenu1. This will assign the popup menu to them.
11. Select the SUIButton component and set its OnClick event to ButtonConnectClick. This will allow us to handle click events on the button.

 8cf37b1e13
 
