# FluentUI.Badge.PCF ![GitHub all releases](https://img.shields.io/github/downloads/drivardxrm/FluentUI.Badge.PCF/total?style=plastic)
 PowerApps Component framework (PCF) Control to render [FluentUI v9](https://react.fluentui.dev/) badges in Dataverse Model-driven forms and Canvas Apps
 
 #### Features:

- **Generic** : Can be bound to most of the available Dataverse fields types (see available input types)
- **Portable** : Works in Model-driven apps, Canvas apps, PowerApps portals
- **Themable** : Supports FluentUI V9 Themes (WebLight, WebDark, TeamsLight, TeamsDark, TeamsHighContrast)

# Parameters
| Parameter         | Description                                                                                  | Default     |
|-------------------|----------------------------------------------------------------------------------------------|----------   |
| Input  | Input column of the badge, can be bound to any available field type (see available input types below) |             |
| Separator  | Optional. Will split the input in several badges. For Multiselect OptionSet (Choices) use semicolon (;). |          |
| Appearance   |  Appearance of the Badge. (filled, ghost,outline, tint)   | filled |
| Size   | Size of the Badge. (small, mediun, large, extra-large) | medium |
| Shape |Shape of the Badge. (circular, rounded, square) |   circular  |
| Color | Color of the Badge. (brand, danger, important, informative, severe, subtle, success, warning) |  brand   |
| Theme | Theme. (WebLight, WebDark, TeamsLight, TeamsDark, TeamsHighContrast) |   WebLight  |

see official documentation of the [FluentUI V9 Badge React control](https://react.fluentui.dev/?path=/docs/components-badge-badge--default) for more info

## Available Input types ##
SingleLine.Text  
SingleLine.Email   
SingleLine.Phone   
SingleLine.Ticker  
SingleLine.URL  
SingleLine.TextArea  
Whole.None  
Currency  
FP  
Decimal  
Lookup.Simple  
DateAndTime.DateAndTime  
DateAndTime.DateOnly  
OptionSet  
TwoOptions  
Enum  
Multiple  
MultiSelectOptionSet  
