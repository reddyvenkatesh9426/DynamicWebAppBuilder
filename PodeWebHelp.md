
NAME
    Add-PodeWebComponentClass
    
SYNTAX
    Add-PodeWebComponentClass -Id <string> -Class <string>  [<CommonParameters>]
    
    Add-PodeWebComponentClass -Type <string> -Name <string> -Class <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Class <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Add-PodeWebCustomTheme
    
SYNTAX
    Add-PodeWebCustomTheme [-Name] <string> [-Url] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Add-PodeWebPage
    
SYNTAX
    Add-PodeWebPage [-Name] <string> [[-DisplayName] <string>] [[-Title] <string>] [[-Group] <string>] 
    [[-Icon] <string>] [[-Layouts] <hashtable[]>] [[-ScriptBlock] <scriptblock>] [[-ArgumentList] <Object[]>] 
    [[-AccessGroups] <string[]>] [[-AccessUsers] <string[]>] [[-EndpointName] <string[]>] [[-Navigation] 
    <hashtable[]>] [[-HelpScriptBlock] <scriptblock>] [-NoAuthentication] [-NoTitle] [-NoBackArrow] 
    [-NoBreadcrumb] [-NewTab] [-Hide] [-NoSidebar] [-PassThru]  [<CommonParameters>]
    
    
PARAMETERS
    -AccessGroups <string[]>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AccessUsers <string[]>
        
        Required?                    false
        Position?                    9
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    10
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Group <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -HelpScriptBlock <scriptblock>
        
        Required?                    false
        Position?                    12
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Hide
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Layouts <hashtable[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Navigation <hashtable[]>
        
        Required?                    false
        Position?                    11
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NewTab
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -NoBackArrow
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoBreadcrumb
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoSidebar
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoTitle
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -PassThru
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Add-PodeWebPageLink
    
SYNTAX
    Add-PodeWebPageLink -Name <string> -ScriptBlock <scriptblock> [-DisplayName <string>] [-Group <string>] 
    [-Icon <string>] [-ArgumentList <Object[]>] [-AccessGroups <string[]>] [-AccessUsers <string[]>] 
    [-EndpointName <string[]>] [-NoAuthentication] [-Hide]  [<CommonParameters>]
    
    Add-PodeWebPageLink -Name <string> -Url <string> [-DisplayName <string>] [-Group <string>] [-Icon 
    <string>] [-AccessGroups <string[]>] [-AccessUsers <string[]>] [-NewTab] [-Hide]  [<CommonParameters>]
    
    
PARAMETERS
    -AccessGroups <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AccessUsers <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -Group <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Hide
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NewTab
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Url
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Url
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Add-PodeWebTableButton
    
SYNTAX
    Add-PodeWebTableButton [-Table] <hashtable> [-Name] <string> [[-DisplayName] <string>] [[-Icon] <string>] 
    [-ScriptBlock] <scriptblock> [[-ArgumentList] <Object[]>] [[-EndpointName] <string[]>] [-WithText]  
    [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Table <hashtable>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -WithText
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Collections.Hashtable
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Clear-PodeWebChart
    
SYNTAX
    Clear-PodeWebChart -Id <string>  [<CommonParameters>]
    
    Clear-PodeWebChart -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Clear-PodeWebCodeEditor
    
SYNTAX
    Clear-PodeWebCodeEditor -Id <string>  [<CommonParameters>]
    
    Clear-PodeWebCodeEditor -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Clear-PodeWebFileStream
    
SYNTAX
    Clear-PodeWebFileStream -Id <string>  [<CommonParameters>]
    
    Clear-PodeWebFileStream -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Clear-PodeWebSelect
    
SYNTAX
    Clear-PodeWebSelect -Name <string>  [<CommonParameters>]
    
    Clear-PodeWebSelect -Id <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Clear-PodeWebTable
    
SYNTAX
    Clear-PodeWebTable -Id <string>  [<CommonParameters>]
    
    Clear-PodeWebTable -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Clear-PodeWebTextbox
    
SYNTAX
    Clear-PodeWebTextbox -Name <string> [-Multiline]  [<CommonParameters>]
    
    Clear-PodeWebTextbox -Id <string> [-Multiline]  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Multiline
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    ConvertTo-PodeWebChartData
    
SYNTAX
    ConvertTo-PodeWebChartData [-Data] <Object> [-LabelProperty] <string> [-DatasetProperty] <string[]>  
    [<CommonParameters>]
    
    
PARAMETERS
    -Data <Object>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DatasetProperty <string[]>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      Dataset
        Dynamic?                     false
        
    -LabelProperty <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      Label
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Object
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    ConvertTo-PodeWebPage
    
SYNTAX
    ConvertTo-PodeWebPage [[-Commands] <string[]>] [[-Module] <string>] [-GroupVerbs] [-NoAuthentication]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Commands <string[]>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -GroupVerbs
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Module <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.String[]
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Disable-PodeWebButton
    
SYNTAX
    Disable-PodeWebButton -Id <string>  [<CommonParameters>]
    
    Disable-PodeWebButton -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Disable-PodeWebCheckbox
    
SYNTAX
    Disable-PodeWebCheckbox -Id <string> [-OptionId <int>]  [<CommonParameters>]
    
    Disable-PodeWebCheckbox -Name <string> [-OptionId <int>]  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -OptionId <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Enable-PodeWebButton
    
SYNTAX
    Enable-PodeWebButton -Id <string>  [<CommonParameters>]
    
    Enable-PodeWebButton -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Enable-PodeWebCheckbox
    
SYNTAX
    Enable-PodeWebCheckbox -Id <string> [-OptionId <int>]  [<CommonParameters>]
    
    Enable-PodeWebCheckbox -Name <string> [-OptionId <int>]  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -OptionId <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Get-PodeWebNavDefault
    
SYNTAX
    Get-PodeWebNavDefault [[-Items] <hashtable[]>]  [<CommonParameters>]
    
    
PARAMETERS
    -Items <hashtable[]>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Get-PodeWebPage
    
SYNTAX
    Get-PodeWebPage [[-Name] <string>] [[-Group] <string>] [-NoGroup]  [<CommonParameters>]
    
    
PARAMETERS
    -Group <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoGroup
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Get-PodeWebTheme
    
SYNTAX
    Get-PodeWebTheme [-IgnoreCookie]  [<CommonParameters>]
    
    
PARAMETERS
    -IgnoreCookie
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Get-PodeWebUsername
    
SYNTAX
    Get-PodeWebUsername  [<CommonParameters>]
    
    
PARAMETERS
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Hide-PodeWebComponent
    
SYNTAX
    Hide-PodeWebComponent -Id <string>  [<CommonParameters>]
    
    Hide-PodeWebComponent -Type <string> -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Hide-PodeWebModal
    
SYNTAX
    Hide-PodeWebModal [-Id <string>]  [<CommonParameters>]
    
    Hide-PodeWebModal [-Name <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Hide-PodeWebTableColumn
    
SYNTAX
    Hide-PodeWebTableColumn -Id <string> -Key <string>  [<CommonParameters>]
    
    Hide-PodeWebTableColumn -Name <string> -Key <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Key <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Import-PodeWebJavaScript
    
SYNTAX
    Import-PodeWebJavaScript [-Url] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Url <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Import-PodeWebStylesheet
    
SYNTAX
    Import-PodeWebStylesheet [-Url] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Url <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Initialize-PodeWebTableColumn
    
SYNTAX
    Initialize-PodeWebTableColumn [-Key] <string> [[-Width] <string>] [[-Alignment] {Left | Right | Center}] 
    [[-Name] <string>] [[-Icon] <string>] [[-Default] <string>] [-Hide]  [<CommonParameters>]
    
    
PARAMETERS
    -Alignment <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Default <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Hide
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Key <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Width <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Invoke-PodeWebButton
    
SYNTAX
    Invoke-PodeWebButton -Id <string>  [<CommonParameters>]
    
    Invoke-PodeWebButton -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Join-PodeWebPath
    
SYNTAX
    Join-PodeWebPath [[-Path] <string>] [[-ChildPath] <string>] [-ReplaceSlashes]  [<CommonParameters>]
    
    
PARAMETERS
    -ChildPath <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Path <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ReplaceSlashes
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Move-PodeWebAccordion
    
SYNTAX
    Move-PodeWebAccordion -Name <string>  [<CommonParameters>]
    
    Move-PodeWebAccordion -Id <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Move-PodeWebPage
    
SYNTAX
    Move-PodeWebPage [-Name] <string> [[-Group] <string>] [[-DataValue] <string>] [-NewTab]  
    [<CommonParameters>]
    
    
PARAMETERS
    -DataValue <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Group <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NewTab
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Move-PodeWebTab
    
SYNTAX
    Move-PodeWebTab -Name <string>  [<CommonParameters>]
    
    Move-PodeWebTab -Id <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Move-PodeWebUrl
    
SYNTAX
    Move-PodeWebUrl [-Url] <string> [-NewTab]  [<CommonParameters>]
    
    
PARAMETERS
    -NewTab
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebAccordion
    
SYNTAX
    New-PodeWebAccordion [[-Id] <string>] [-Bellows] <hashtable[]> [[-CssClass] <string[]>] [[-CssStyle] 
    <hashtable>] [[-CycleInterval] <int>] [[-Mode] {Normal | Collapsed | Expanded}] [-Cycle]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Bellows <hashtable[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Cycle
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CycleInterval <int>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Mode <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebAlert
    
SYNTAX
    New-PodeWebAlert -Value <string> [-Id <string>] [-Type {Note | Tip | Important | Info | Warning | Error | 
    Success}] [-CssClass <string[]>] [-CssStyle <hashtable>]  [<CommonParameters>]
    
    New-PodeWebAlert -Content <hashtable[]> [-Id <string>] [-Type {Note | Tip | Important | Info | Warning | 
    Error | Success}] [-CssClass <string[]>] [-CssStyle <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Content
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Value
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebAudio
    
SYNTAX
    New-PodeWebAudio [[-Name] <string>] [[-Id] <string>] [-Source] <hashtable[]> [[-Track] <hashtable[]>] 
    [[-NotSupportedText] <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [[-Width] <string>] 
    [-Muted] [-AutoPlay] [-AutoBuffer] [-Loop] [-NoControls] [-NoDownload]  [<CommonParameters>]
    
    
PARAMETERS
    -AutoBuffer
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AutoPlay
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Loop
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Muted
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoControls
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoDownload
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NotSupportedText <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Source <hashtable[]>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Track <hashtable[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Width <string>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebAudioSource
    
SYNTAX
    New-PodeWebAudioSource [-Url] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Url <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebBadge
    
SYNTAX
    New-PodeWebBadge [[-Id] <string>] [[-Colour] {Blue | Grey | Green | Red | Yellow | Cyan | Light | Dark}] 
    [-Value] <string> [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -Colour <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebBellow
    
SYNTAX
    New-PodeWebBellow [-Name] <string> [[-DisplayName] <string>] [[-Content] <hashtable[]>] [[-Icon] 
    <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -Content <hashtable[]>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebBreadcrumbItem
    
SYNTAX
    New-PodeWebBreadcrumbItem [-Name] <string> [[-DisplayName] <string>] [-Url] <string> [-Active]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Active
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebButton
    
SYNTAX
    New-PodeWebButton -Name <string> -ScriptBlock <scriptblock> [-DisplayName <string>] [-Id <string>] 
    [-DataValue <string>] [-Icon <string>] [-ArgumentList <Object[]>] [-Colour {Blue | Grey | Green | Red | 
    Yellow | Cyan | Light | Dark}] [-Size {Normal | Small | Large}] [-CssClass <string[]>] [-CssStyle 
    <hashtable>] [-EndpointName <string[]>] [-NoAuthentication] [-IconOnly] [-NewLine] [-Outline] [-Disabled] 
    [-FullWidth]  [<CommonParameters>]
    
    New-PodeWebButton -Name <string> -Url <string> [-DisplayName <string>] [-Id <string>] [-Icon <string>] 
    [-Colour {Blue | Grey | Green | Red | Yellow | Cyan | Light | Dark}] [-Size {Normal | Small | Large}] 
    [-CssClass <string[]>] [-CssStyle <hashtable>] [-EndpointName <string[]>] [-IconOnly] [-NewLine] 
    [-NewTab] [-Outline] [-Disabled] [-FullWidth]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -Colour <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DataValue <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -Disabled
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -FullWidth
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -IconOnly
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NewLine
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NewTab
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Url
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      NoAuth
        Dynamic?                     false
        
    -Outline
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -Size <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Url
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCard
    
SYNTAX
    New-PodeWebCard [[-Name] <string>] [[-DisplayName] <string>] [[-Id] <string>] [-Content] <hashtable[]> 
    [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [[-Icon] <string>] [-NoTitle] [-NoHide]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoHide
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoTitle
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCarousel
    
SYNTAX
    New-PodeWebCarousel [[-Id] <string>] [-Slides] <hashtable[]> [[-CssClass] <string[]>] [[-CssStyle] 
    <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Slides <hashtable[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCell
    
SYNTAX
    New-PodeWebCell [[-Id] <string>] [-Content] <hashtable[]> [[-Width] <string>] [[-Alignment] {Left | Right 
    | Center}] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -Alignment <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Width <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebChart
    
SYNTAX
    New-PodeWebChart [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [[-Message] <string>] 
    [-ScriptBlock] <scriptblock> [[-Type] {line | pie | doughnut | bar}] [[-MaxItems] <int>] [[-Height] 
    <string>] [[-ArgumentList] <Object[]>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] 
    [[-EndpointName] <string[]>] [[-MinX] <int>] [[-MaxX] <int>] [[-MinY] <int>] [[-MaxY] <int>] 
    [[-RefreshInterval] <int>] [[-Colours] <string[]>] [-NoAuthentication] [-Append] [-TimeLabels] 
    [-AutoRefresh] [-NoRefresh] [-NoLegend] [-AsCard]  [<CommonParameters>]
    
    
PARAMETERS
    -Append
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AsCard
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AutoRefresh
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Colours <string[]>
        
        Required?                    false
        Position?                    17
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    9
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    10
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    11
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Height <string>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MaxItems <int>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MaxX <int>
        
        Required?                    false
        Position?                    13
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MaxY <int>
        
        Required?                    false
        Position?                    15
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Message <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MinX <int>
        
        Required?                    false
        Position?                    12
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MinY <int>
        
        Required?                    false
        Position?                    14
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -NoLegend
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoRefresh
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -RefreshInterval <int>
        
        Required?                    false
        Position?                    16
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -TimeLabels
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCheckbox
    
SYNTAX
    New-PodeWebCheckbox -Name <string> [-DisplayName <string>] [-Id <string>] [-Options <string[]>] 
    [-DisplayOptions <string[]>] [-CssClass <string[]>] [-CssStyle <hashtable>] [-Inline] [-AsSwitch] 
    [-Checked] [-Disabled] [-NoForm] [-Required]  [<CommonParameters>]
    
    
PARAMETERS
    -AsSwitch
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Checked
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Disabled
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayOptions <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Multiple
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Inline
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Multiple
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoForm
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Options <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Multiple
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCode
    
SYNTAX
    New-PodeWebCode [[-Id] <string>] [-Value] <string> [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  
    [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCodeBlock
    
SYNTAX
    New-PodeWebCodeBlock [[-Id] <string>] [[-Value] <string>] [[-Language] <string>] [[-CssClass] <string[]>] 
    [[-CssStyle] <hashtable>] [-Scrollable] [-NoHighlight]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Language <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoHighlight
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Scrollable
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCodeEditor
    
SYNTAX
    New-PodeWebCodeEditor [-Name] <string> [[-Id] <string>] [[-Language] <string>] [[-Theme] { | vs | vs-dark 
    | hc-black}] [[-Value] <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [[-Upload] 
    <scriptblock>] [[-ArgumentList] <Object[]>] [[-EndpointName] <string[]>] [-NoAuthentication] [-ReadOnly] 
    [-AsCard]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AsCard
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    9
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Language <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ReadOnly
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Theme <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Upload <scriptblock>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebComment
    
SYNTAX
    New-PodeWebComment [[-Id] <string>] [-Icon] <string> [-Username] <string> [-Message] <string> 
    [[-TimeStamp] <datetime>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Message <string>
        
        Required?                    true
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -TimeStamp <datetime>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Username <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebContainer
    
SYNTAX
    New-PodeWebContainer [[-Id] <string>] [-Content] <hashtable[]> [[-CssClass] <string[]>] [[-CssStyle] 
    <hashtable>] [-NoBackground] [-Hide]  [<CommonParameters>]
    
    
PARAMETERS
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Hide
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoBackground
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCounterChart
    
SYNTAX
    New-PodeWebCounterChart [-Counter] <string> [[-Name] <string>] [[-DisplayName] <string>] [[-CssClass] 
    <string[]>] [[-CssStyle] <hashtable>] [[-MaxItems] <int>] [[-MinX] <int>] [[-MaxX] <int>] [[-MinY] <int>] 
    [[-MaxY] <int>] [[-Colours] <string[]>] [-NoAuthentication] [-NoLegend] [-AsCard]  [<CommonParameters>]
    
    
PARAMETERS
    -AsCard
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Colours <string[]>
        
        Required?                    false
        Position?                    10
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Counter <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MaxItems <int>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MaxX <int>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MaxY <int>
        
        Required?                    false
        Position?                    9
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MinX <int>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MinY <int>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -NoLegend
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebCredential
    
SYNTAX
    New-PodeWebCredential [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [[-HelpText] <string>] 
    [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [[-DisplayUsername] <string>] [[-DisplayPassword] 
    <string>] [[-Type] {Username | Password}] [-ReadOnly] [-NoLabels] [-Required]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayPassword <string>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayUsername <string>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -HelpText <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoLabels
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ReadOnly
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string[]>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebDateTime
    
SYNTAX
    New-PodeWebDateTime [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [[-HelpText] <string>] 
    [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [[-DisplayDate] <string>] [[-DisplayTime] <string>] 
    [[-Type] {Date | Time}] [-ReadOnly] [-NoLabels] [-Required]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayDate <string>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayTime <string>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -HelpText <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoLabels
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ReadOnly
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string[]>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebFileStream
    
SYNTAX
    New-PodeWebFileStream [[-Name] <string>] [[-Id] <string>] [-Url] <string> [[-Height] <int>] [[-CssClass] 
    <string[]>] [[-CssStyle] <hashtable>] [[-Interval] <int>] [[-Icon] <string>] [-NoHeader]  
    [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Height <int>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Interval <int>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoHeader
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebFileUpload
    
SYNTAX
    New-PodeWebFileUpload [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [[-Accept] <string[]>] 
    [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [-NoForm] [-Required]  [<CommonParameters>]
    
    
PARAMETERS
    -Accept <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoForm
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebForm
    
SYNTAX
    New-PodeWebForm [-Name] <string> [[-Id] <string>] [[-Message] <string>] [-Content] <hashtable[]> 
    [-ScriptBlock] <scriptblock> [[-ArgumentList] <Object[]>] [[-CssClass] <string[]>] [[-CssStyle] 
    <hashtable>] [[-EndpointName] <string[]>] [[-Method] {Get | Post}] [[-Action] <string>] [[-SubmitText] 
    <string>] [[-ResetText] <string>] [-NoAuthentication] [-AsCard] [-ShowReset]  [<CommonParameters>]
    
    
PARAMETERS
    -Action <string>
        
        Required?                    false
        Position?                    10
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AsCard
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Message <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Method <string>
        
        Required?                    false
        Position?                    9
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ResetText <string>
        
        Required?                    false
        Position?                    12
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ShowReset
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -SubmitText <string>
        
        Required?                    false
        Position?                    11
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebGrid
    
SYNTAX
    New-PodeWebGrid [[-Id] <string>] [-Cells] <hashtable[]> [[-Width] <int>] [[-CssClass] <string[]>] 
    [[-CssStyle] <hashtable>] [-Vertical]  [<CommonParameters>]
    
    
PARAMETERS
    -Cells <hashtable[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Vertical
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Width <int>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebHeader
    
SYNTAX
    New-PodeWebHeader [[-Id] <string>] [-Size] {1 | 2 | 3 | 4 | 5 | 6} [-Value] <string> [[-Secondary] 
    <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Secondary <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Size <int>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebHero
    
SYNTAX
    New-PodeWebHero [[-Id] <string>] [-Title] <string> [-Message] <string> [[-Content] <hashtable[]>] 
    [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -Content <hashtable[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Message <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebHidden
    
SYNTAX
    New-PodeWebHidden [-Name] <string> [[-Id] <string>] [-Value] <string> [[-CssClass] <string[]>] 
    [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebIcon
    
SYNTAX
    New-PodeWebIcon -Name <string> [-Id <string>] [-Colour <string>] [-CssClass <string[]>] [-CssStyle 
    <hashtable>] [-Title <string>] [-Rotate {0 | 45 | 90 | 135 | 180 | 225 | 270 | 315}] [-Spin]  
    [<CommonParameters>]
    
    New-PodeWebIcon -Name <string> [-Id <string>] [-Colour <string>] [-CssClass <string[]>] [-CssStyle 
    <hashtable>] [-Title <string>] [-Flip {Horizontal | Vertical}] [-Spin]  [<CommonParameters>]
    
    
PARAMETERS
    -Colour <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Flip <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Flip
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Rotate <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Rotate
        Aliases                      None
        Dynamic?                     false
        
    -Spin
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebIFrame
    
SYNTAX
    New-PodeWebIFrame [[-Name] <string>] [[-Id] <string>] [-Url] <string> [[-Title] <string>] [[-CssClass] 
    <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebImage
    
SYNTAX
    New-PodeWebImage [[-Id] <string>] [-Source] <string> [[-Title] <string>] [[-Alignment] {Left | Right | 
    Center}] [[-Height] <string>] [[-Width] <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Alignment <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Height <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Source <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      Alt
        Dynamic?                     false
        
    -Width <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebLine
    
SYNTAX
    New-PodeWebLine [[-Id] <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebLink
    
SYNTAX
    New-PodeWebLink [[-Id] <string>] [-Source] <string> [-Value] <string> [[-CssClass] <string[]>] 
    [[-CssStyle] <hashtable>] [-NewTab]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NewTab
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Source <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebList
    
SYNTAX
    New-PodeWebList -Values <string[]> [-Id <string>] [-CssClass <string[]>] [-CssStyle <hashtable>] 
    [-Numbered]  [<CommonParameters>]
    
    New-PodeWebList -Items <hashtable[]> [-Id <string>] [-CssClass <string[]>] [-CssStyle <hashtable>] 
    [-Numbered]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Items <hashtable[]>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Items
        Aliases                      None
        Dynamic?                     false
        
    -Numbered
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Values <string[]>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Values
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebListItem
    
SYNTAX
    New-PodeWebListItem [-Content] <hashtable[]> [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebMediaTrack
    
SYNTAX
    New-PodeWebMediaTrack [-Url] <string> [[-Language] <string>] [[-Title] <string>] [[-Type] {captions | 
    chapters | descriptions | metadata | subtitles}] [-Default]  [<CommonParameters>]
    
    
PARAMETERS
    -Default
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Language <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebMinMax
    
SYNTAX
    New-PodeWebMinMax -Name <string> [-DisplayName <string>] [-Id <string>] [-HelpText <string>] [-MinValue 
    <double>] [-MaxValue <double>] [-PrependText <string>] [-PrependIcon <string>] [-AppendText <string>] 
    [-AppendIcon <string>] [-CssClass <string[]>] [-CssStyle <hashtable>] [-DisplayMin <string>] [-DisplayMax 
    <string>] [-Type {Min | Max}] [-ReadOnly] [-NoLabels] [-Required]  [<CommonParameters>]
    
    
PARAMETERS
    -AppendIcon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -AppendText <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayMax <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayMin <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -HelpText <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MaxValue <double>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MinValue <double>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoLabels
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -PrependIcon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -PrependText <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -ReadOnly
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebModal
    
SYNTAX
    New-PodeWebModal [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [-Content] <hashtable[]> 
    [[-Icon] <string>] [[-SubmitText] <string>] [[-CloseText] <string>] [[-Size] {Small | Medium | Large}] 
    [[-ScriptBlock] <scriptblock>] [[-ArgumentList] <Object[]>] [[-CssClass] <string[]>] [[-CssStyle] 
    <hashtable>] [[-EndpointName] <string[]>] [[-Method] {Get | Post}] [[-Action] <string>] [-AsForm] 
    [-NoAuthentication]  [<CommonParameters>]
    
    
PARAMETERS
    -Action <string>
        
        Required?                    false
        Position?                    14
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    9
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AsForm
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CloseText <string>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    10
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    11
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    12
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Method <string>
        
        Required?                    false
        Position?                    13
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Size <string>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -SubmitText <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebNavDivider
    
SYNTAX
    New-PodeWebNavDivider  [<CommonParameters>]
    
    
PARAMETERS
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebNavDropdown
    
SYNTAX
    New-PodeWebNavDropdown [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [-Items] <hashtable[]> 
    [[-Icon] <string>] [-Disabled] [-Hover]  [<CommonParameters>]
    
    
PARAMETERS
    -Disabled
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Hover
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Items <hashtable[]>
        
        Required?                    true
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebNavLink
    
SYNTAX
    New-PodeWebNavLink -Name <string> -Url <string> [-DisplayName <string>] [-Id <string>] [-Icon <string>] 
    [-Disabled] [-NewTab]  [<CommonParameters>]
    
    New-PodeWebNavLink -Name <string> -ScriptBlock <scriptblock> [-DisplayName <string>] [-Id <string>] 
    [-ArgumentList <Object[]>] [-Icon <string>] [-Disabled] [-NoAuthentication]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -Disabled
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NewTab
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Url
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Url
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebParagraph
    
SYNTAX
    New-PodeWebParagraph -Value <string> [-Id <string>] [-Alignment {Left | Right | Center}] [-CssClass 
    <string[]>] [-CssStyle <hashtable>]  [<CommonParameters>]
    
    New-PodeWebParagraph -Elements <hashtable[]> [-Id <string>] [-Alignment {Left | Right | Center}] 
    [-CssClass <string[]>] [-CssStyle <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -Alignment <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Elements <hashtable[]>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Elements
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Value
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebProgress
    
SYNTAX
    New-PodeWebProgress [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [[-Value] <int>] [[-Min] 
    <int>] [[-Max] <int>] [[-Colour] {Blue | Grey | Green | Red | Yellow | Cyan | Light | Dark}] [[-CssClass] 
    <string[]>] [[-CssStyle] <hashtable>] [-ShowValue] [-Striped] [-Animated]  [<CommonParameters>]
    
    
PARAMETERS
    -Animated
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Colour <string>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Max <int>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Min <int>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ShowValue
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Striped
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <int>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebQuote
    
SYNTAX
    New-PodeWebQuote [[-Id] <string>] [[-Alignment] {Left | Right | Center}] [-Value] <string> [[-Source] 
    <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -Alignment <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Source <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebRadio
    
SYNTAX
    New-PodeWebRadio [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [-Options] <string[]> 
    [[-DisplayOptions] <string[]>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [-Inline] [-Disabled] 
    [-NoForm] [-Required]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Disabled
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayOptions <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Inline
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoForm
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Options <string[]>
        
        Required?                    true
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebRange
    
SYNTAX
    New-PodeWebRange [-Name] <string> [[-DisplayName] <string>] [[-Id] <string>] [[-Value] <int>] [[-Min] 
    <int>] [[-Max] <int>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [-Disabled] [-ShowValue] 
    [-NoForm] [-Required]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Disabled
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Max <int>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Min <int>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoForm
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ShowValue
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <int>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebRaw
    
SYNTAX
    New-PodeWebRaw [-Value] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Value <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebSelect
    
SYNTAX
    New-PodeWebSelect -Name <string> [-DisplayName <string>] [-Id <string>] [-Options <string[]>] 
    [-DisplayOptions <string[]>] [-SelectedValue <string[]>] [-Size <int>] [-CssClass <string[]>] [-CssStyle 
    <hashtable>] [-Multiple] [-NoForm] [-Required]  [<CommonParameters>]
    
    New-PodeWebSelect -Name <string> [-DisplayName <string>] [-Id <string>] [-ScriptBlock <scriptblock>] 
    [-ArgumentList <Object[]>] [-SelectedValue <string[]>] [-Size <int>] [-CssClass <string[]>] [-CssStyle 
    <hashtable>] [-Multiple] [-NoForm] [-Required]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayOptions <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Options
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Multiple
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoForm
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Options <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Options
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    -SelectedValue <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Size <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebSlide
    
SYNTAX
    New-PodeWebSlide [-Content] <hashtable[]> [[-Title] <string>] [[-Message] <string>] [[-CssClass] 
    <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Message <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebSpinner
    
SYNTAX
    New-PodeWebSpinner [[-Id] <string>] [[-Colour] <string>] [[-CssClass] <string[]>] [[-CssStyle] 
    <hashtable>] [[-Title] <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Colour <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebStep
    
SYNTAX
    New-PodeWebStep [-Name] <string> [[-DisplayName] <string>] [[-Content] <hashtable[]>] [[-ScriptBlock] 
    <scriptblock>] [[-ArgumentList] <Object[]>] [[-Icon] <string>] [[-EndpointName] <string[]>] [[-CssClass] 
    <string[]>] [[-CssStyle] <hashtable>] [-NoAuthentication]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Content <hashtable[]>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebSteps
    
SYNTAX
    New-PodeWebSteps [-Name] <string> [[-Id] <string>] [-Steps] <hashtable[]> [[-CssClass] <string[]>] 
    [[-CssStyle] <hashtable>] [-ScriptBlock] <scriptblock> [[-ArgumentList] <Object[]>] [[-EndpointName] 
    <string[]>] [-NoAuthentication]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Steps <hashtable[]>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebTab
    
SYNTAX
    New-PodeWebTab [[-Id] <string>] [-Name] <string> [[-DisplayName] <string>] [-Layouts] <hashtable[]> 
    [[-Icon] <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Layouts <hashtable[]>
        
        Required?                    true
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebTable
    
SYNTAX
    New-PodeWebTable -Name <string> [-DisplayName <string>] [-Id <string>] [-Message <string>] [-DataColumn 
    <string>] [-Columns <hashtable[]>] [-CssClass <string[]>] [-CssStyle <hashtable>] [-EndpointName 
    <string[]>] [-ClickScriptBlock <scriptblock>] [-RefreshInterval <int>] [-Compact] [-Filter] 
    [-SimpleFilter] [-Sort] [-SimpleSort] [-Click] [-Paginate] [-NoExport] [-NoRefresh] [-NoAuthentication] 
    [-AsCard]  [<CommonParameters>]
    
    New-PodeWebTable -Name <string> [-DisplayName <string>] [-Id <string>] [-Message <string>] [-DataColumn 
    <string>] [-Columns <hashtable[]>] [-ScriptBlock <scriptblock>] [-ArgumentList <Object[]>] [-PageSize 
    <int>] [-CssClass <string[]>] [-CssStyle <hashtable>] [-EndpointName <string[]>] [-ClickScriptBlock 
    <scriptblock>] [-RefreshInterval <int>] [-Compact] [-Filter] [-SimpleFilter] [-Sort] [-SimpleSort] 
    [-Click] [-Paginate] [-NoExport] [-NoRefresh] [-NoAuthentication] [-AutoRefresh] [-AsCard]  
    [<CommonParameters>]
    
    New-PodeWebTable -Name <string> [-DisplayName <string>] [-Id <string>] [-Message <string>] [-DataColumn 
    <string>] [-Columns <hashtable[]>] [-CsvFilePath <string>] [-PageSize <int>] [-CssClass <string[]>] 
    [-CssStyle <hashtable>] [-EndpointName <string[]>] [-ClickScriptBlock <scriptblock>] [-RefreshInterval 
    <int>] [-Compact] [-Filter] [-SimpleFilter] [-Sort] [-SimpleSort] [-Click] [-Paginate] [-NoExport] 
    [-NoRefresh] [-NoAuthentication] [-AutoRefresh] [-AsCard]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Dynamic
        Aliases                      None
        Dynamic?                     false
        
    -AsCard
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AutoRefresh
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Csv, Dynamic
        Aliases                      None
        Dynamic?                     false
        
    -Click
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ClickScriptBlock <scriptblock>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Columns <hashtable[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Compact
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CsvFilePath <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Csv
        Aliases                      None
        Dynamic?                     false
        
    -DataColumn <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Filter
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Message <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -NoExport
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoRefresh
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -PageSize <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Csv, Dynamic
        Aliases                      PageAmount
        Dynamic?                     false
        
    -Paginate
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Csv, Dynamic, Default
        Aliases                      None
        Dynamic?                     false
        
    -RefreshInterval <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Dynamic
        Aliases                      None
        Dynamic?                     false
        
    -SimpleFilter
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -SimpleSort
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Sort
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebTabs
    
SYNTAX
    New-PodeWebTabs [[-Id] <string>] [-Tabs] <hashtable[]> [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] 
    [[-CycleInterval] <int>] [-Cycle]  [<CommonParameters>]
    
    
PARAMETERS
    -CssClass <string[]>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Cycle
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CycleInterval <int>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Tabs <hashtable[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebText
    
SYNTAX
    New-PodeWebText [-Id <string>] [-Value <string>] [-Style {Normal | Underlined | StrikeThrough | Deleted | 
    Inserted | Italics | Bold | Small}] [-CssClass <string[]>] [-CssStyle <hashtable>] [-Pronunciation 
    <string>]  [<CommonParameters>]
    
    New-PodeWebText [-Id <string>] [-Value <string>] [-Style {Normal | Underlined | StrikeThrough | Deleted | 
    Inserted | Italics | Bold | Small}] [-Alignment {Left | Right | Center}] [-CssClass <string[]>] 
    [-CssStyle <hashtable>] [-Pronunciation <string>] [-InParagraph]  [<CommonParameters>]
    
    
PARAMETERS
    -Alignment <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Paragraph
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -InParagraph
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Paragraph
        Aliases                      None
        Dynamic?                     false
        
    -Pronunciation <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Style <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebTextbox
    
SYNTAX
    New-PodeWebTextbox -Name <string> [-DisplayName <string>] [-Id <string>] [-Type {Text | Email | Password 
    | Number | Date | Time | File | DateTime}] [-Placeholder <string>] [-Width <string>] [-HelpText <string>] 
    [-PrependText <string>] [-PrependIcon <string>] [-AppendText <string>] [-AppendIcon <string>] [-Value 
    <string>] [-AutoComplete <scriptblock>] [-CssClass <string[]>] [-CssStyle <hashtable>] [-EndpointName 
    <string[]>] [-Preformat] [-ReadOnly] [-NoAuthentication] [-NoForm] [-Required] [-AutoFocus] 
    [-DynamicLabel] [-MaxLength <int>]  [<CommonParameters>]
    
    New-PodeWebTextbox -Name <string> [-DisplayName <string>] [-Id <string>] [-Placeholder <string>] [-Size 
    <int>] [-Width <string>] [-HelpText <string>] [-Value <string>] [-CssClass <string[]>] [-CssStyle 
    <hashtable>] [-EndpointName <string[]>] [-Multiline] [-Preformat] [-ReadOnly] [-NoForm] [-Required] 
    [-AutoFocus] [-DynamicLabel] [-MaxLength <int>]  [<CommonParameters>]
    
    
PARAMETERS
    -AppendIcon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -AppendText <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -AutoComplete <scriptblock>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -AutoFocus
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DynamicLabel
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -HelpText <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -MaxLength <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Multiline
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Multi
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      NoAuth
        Dynamic?                     false
        
    -NoForm
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Placeholder <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Preformat
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -PrependIcon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -PrependText <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -ReadOnly
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Required
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Size <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Multi
        Aliases                      Height
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Single
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Width <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebTile
    
SYNTAX
    New-PodeWebTile -Name <string> -ScriptBlock <scriptblock> [-DisplayName <string>] [-Id <string>] [-Icon 
    <string>] [-ArgumentList <Object[]>] [-CssClass <string[]>] [-CssStyle <hashtable>] [-EndpointName 
    <string[]>] [-ClickScriptBlock <scriptblock>] [-Colour {Blue | Grey | Green | Red | Yellow | Cyan | Light 
    | Dark}] [-RefreshInterval <int>] [-NoRefresh] [-NoAuthentication] [-AutoRefresh] [-NewLine]  
    [<CommonParameters>]
    
    New-PodeWebTile -Name <string> -Content <hashtable[]> [-DisplayName <string>] [-Id <string>] [-Icon 
    <string>] [-ArgumentList <Object[]>] [-CssClass <string[]>] [-CssStyle <hashtable>] [-EndpointName 
    <string[]>] [-ClickScriptBlock <scriptblock>] [-Colour {Blue | Grey | Green | Red | Yellow | Cyan | Light 
    | Dark}] [-RefreshInterval <int>] [-NoRefresh] [-NoAuthentication] [-AutoRefresh] [-NewLine]  
    [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AutoRefresh
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ClickScriptBlock <scriptblock>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Colour <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Content <hashtable[]>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Content
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NewLine
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -NoRefresh
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -RefreshInterval <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ScriptBlock
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebTimer
    
SYNTAX
    New-PodeWebTimer [[-Name] <string>] [[-Id] <string>] [[-Interval] <int>] [-ScriptBlock] <scriptblock> 
    [[-ArgumentList] <Object[]>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] [[-EndpointName] 
    <string[]>] [-NoAuthentication]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Interval <int>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebVideo
    
SYNTAX
    New-PodeWebVideo [[-Name] <string>] [[-Id] <string>] [-Source] <hashtable[]> [[-Track] <hashtable[]>] 
    [[-Thumbnail] <string>] [[-NotSupportedText] <string>] [[-CssClass] <string[]>] [[-CssStyle] <hashtable>] 
    [[-Width] <string>] [[-Height] <string>] [-Muted] [-AutoPlay] [-AutoBuffer] [-Loop] [-NoControls] 
    [-NoDownload] [-NoPictureInPicture]  [<CommonParameters>]
    
    
PARAMETERS
    -AutoBuffer
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AutoPlay
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssClass <string[]>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -CssStyle <hashtable>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Height <string>
        
        Required?                    false
        Position?                    9
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Loop
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Muted
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoControls
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoDownload
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoPictureInPicture
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NotSupportedText <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Source <hashtable[]>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Thumbnail <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Track <hashtable[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Width <string>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    New-PodeWebVideoSource
    
SYNTAX
    New-PodeWebVideoSource [-Url] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Url <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Out-PodeWebBreadcrumb
    
SYNTAX
    Out-PodeWebBreadcrumb [[-Items] <hashtable[]>]  [<CommonParameters>]
    
    
PARAMETERS
    -Items <hashtable[]>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Out-PodeWebChart
    
SYNTAX
    Out-PodeWebChart [-Data] <Object> [[-Type] {line | pie | doughnut | bar}]  [<CommonParameters>]
    
    
PARAMETERS
    -Data <Object>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Object
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Out-PodeWebError
    
SYNTAX
    Out-PodeWebError [-Message] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Message <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Out-PodeWebTable
    
SYNTAX
    Out-PodeWebTable [-Data] <Object> [[-Columns] <hashtable[]>] [-Sort]  [<CommonParameters>]
    
    
PARAMETERS
    -Columns <hashtable[]>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Data <Object>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Sort
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Object
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Out-PodeWebTextbox
    
SYNTAX
    Out-PodeWebTextbox [-Value] <Object> [[-Size] <int>] [-AsJson] [-Multiline] [-Preformat] [-ReadOnly]  
    [<CommonParameters>]
    
    
PARAMETERS
    -AsJson
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Multiline
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Preformat
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ReadOnly
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Size <int>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      Height
        Dynamic?                     false
        
    -Value <Object>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      Data
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Object
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Out-PodeWebValidation
    
SYNTAX
    Out-PodeWebValidation -Name <string> -Message <string>  [<CommonParameters>]
    
    Out-PodeWebValidation -Id <string> -Message <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Message <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Register-PodeWebEvent
    
SYNTAX
    Register-PodeWebEvent [-Component] <hashtable> [-Type] {Change | Focus | FocusOut | Click | MouseOver | 
    MouseOut | KeyDown | KeyUp} [-ScriptBlock] <scriptblock> [[-ArgumentList] <Object[]>] [-NoAuthentication] 
     [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Component <hashtable>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Collections.Hashtable
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Register-PodeWebMediaEvent
    
SYNTAX
    Register-PodeWebMediaEvent [-Component] <hashtable> [-Type] {CanPlay | Pause | Play | Ended} 
    [-ScriptBlock] <scriptblock> [[-ArgumentList] <Object[]>] [-NoAuthentication]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Component <hashtable>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Collections.Hashtable
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Register-PodeWebPageEvent
    
SYNTAX
    Register-PodeWebPageEvent [-Page] <hashtable> [-Type] {Load | Unload | BeforeUnload} [-ScriptBlock] 
    <scriptblock> [[-ArgumentList] <Object[]>] [-NoAuthentication] [-PassThru]  [<CommonParameters>]
    
    
PARAMETERS
    -ArgumentList <Object[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -Page <hashtable>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -PassThru
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ScriptBlock <scriptblock>
        
        Required?                    true
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string[]>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Collections.Hashtable
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Remove-PodeWebComponentClass
    
SYNTAX
    Remove-PodeWebComponentClass -Id <string> -Class <string>  [<CommonParameters>]
    
    Remove-PodeWebComponentClass -Type <string> -Name <string> -Class <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Class <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Remove-PodeWebComponentStyle
    
SYNTAX
    Remove-PodeWebComponentStyle -Id <string> -Property <string>  [<CommonParameters>]
    
    Remove-PodeWebComponentStyle -Type <string> -Name <string> -Property <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Property <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Reset-PodeWebAudio
    
SYNTAX
    Reset-PodeWebAudio -Id <string>  [<CommonParameters>]
    
    Reset-PodeWebAudio -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Reset-PodeWebForm
    
SYNTAX
    Reset-PodeWebForm -Name <string>  [<CommonParameters>]
    
    Reset-PodeWebForm -Id <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Reset-PodeWebPage
    
SYNTAX
    Reset-PodeWebPage  [<CommonParameters>]
    
    
PARAMETERS
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Reset-PodeWebTheme
    
SYNTAX
    Reset-PodeWebTheme  [<CommonParameters>]
    
    
PARAMETERS
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Reset-PodeWebVideo
    
SYNTAX
    Reset-PodeWebVideo -Id <string>  [<CommonParameters>]
    
    Reset-PodeWebVideo -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Restart-PodeWebFileStream
    
SYNTAX
    Restart-PodeWebFileStream -Id <string>  [<CommonParameters>]
    
    Restart-PodeWebFileStream -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Set-PodeWebAuth
    
SYNTAX
    Set-PodeWebAuth [-Authentication] <string> [[-UsernameProperty] <string>] [[-GroupProperty] <string>] 
    [[-AvatarProperty] <string>] [[-ThemeProperty] <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Authentication <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AvatarProperty <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -GroupProperty <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ThemeProperty <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -UsernameProperty <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Set-PodeWebBreadcrumb
    
SYNTAX
    Set-PodeWebBreadcrumb [[-Items] <hashtable[]>]  [<CommonParameters>]
    
    
PARAMETERS
    -Items <hashtable[]>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Set-PodeWebComponentStyle
    
SYNTAX
    Set-PodeWebComponentStyle -Id <string> -Property <string> [-Value <string>]  [<CommonParameters>]
    
    Set-PodeWebComponentStyle -Type <string> -Name <string> -Property <string> [-Value <string>]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Property <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Set-PodeWebHomePage
    
SYNTAX
    Set-PodeWebHomePage [[-Layouts] <hashtable[]>] [[-DisplayName] <string>] [[-Title] <string>] 
    [[-Navigation] <hashtable[]>] [-NoAuthentication] [-NoTitle] [-PassThru]  [<CommonParameters>]
    
    
PARAMETERS
    -DisplayName <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Layouts <hashtable[]>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Navigation <hashtable[]>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoAuthentication
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      NoAuth
        Dynamic?                     false
        
    -NoTitle
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -PassThru
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Set-PodeWebLoginPage
    
SYNTAX
    Set-PodeWebLoginPage [-Authentication] <string> [[-Content] <hashtable[]>] [[-Logo] <string>] [[-LogoUrl] 
    <string>] [[-Copyright] <string>] [[-UsernameProperty] <string>] [[-GroupProperty] <string>] 
    [[-AvatarProperty] <string>] [[-ThemeProperty] <string>] [[-BackgroundImage] <string>] [[-SignInMessage] 
    <string>] [-PassThru]  [<CommonParameters>]
    
    
PARAMETERS
    -Authentication <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -AvatarProperty <string>
        
        Required?                    false
        Position?                    7
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -BackgroundImage <string>
        
        Required?                    false
        Position?                    9
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Content <hashtable[]>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Copyright <string>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -GroupProperty <string>
        
        Required?                    false
        Position?                    6
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Logo <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      Icon
        Dynamic?                     false
        
    -LogoUrl <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      IconUrl
        Dynamic?                     false
        
    -PassThru
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -SignInMessage <string>
        
        Required?                    false
        Position?                    10
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ThemeProperty <string>
        
        Required?                    false
        Position?                    8
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -UsernameProperty <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Set-PodeWebNavDefault
    
SYNTAX
    Set-PodeWebNavDefault [-Items] <hashtable[]>  [<CommonParameters>]
    
    
PARAMETERS
    -Items <hashtable[]>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Set-PodeWebSelect
    
SYNTAX
    Set-PodeWebSelect -Name <string> -Value <string>  [<CommonParameters>]
    
    Set-PodeWebSelect -Id <string> -Value <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.String
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Set-PodeWebSocial
    
SYNTAX
    Set-PodeWebSocial [-Type] {GitHub | Twitter | Facebook | LinkedIn | Twitch | GitLab | Instagram | 
    Telegram | Pinterest | Slack | Discord | BitBucket | Jira | YouTube} [-Url] <string> [[-Tooltip] 
    <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Tooltip <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Show-PodeWebComponent
    
SYNTAX
    Show-PodeWebComponent -Id <string>  [<CommonParameters>]
    
    Show-PodeWebComponent -Type <string> -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Type <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Show-PodeWebModal
    
SYNTAX
    Show-PodeWebModal -Id <string> [-DataValue <string>] [-Actions <hashtable[]>]  [<CommonParameters>]
    
    Show-PodeWebModal -Name <string> [-DataValue <string>] [-Actions <hashtable[]>]  [<CommonParameters>]
    
    
PARAMETERS
    -Actions <hashtable[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DataValue <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Show-PodeWebNotification
    
SYNTAX
    Show-PodeWebNotification [-Title] <string> [[-Body] <string>] [[-Icon] <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Body <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Show-PodeWebTableColumn
    
SYNTAX
    Show-PodeWebTableColumn -Id <string> -Key <string>  [<CommonParameters>]
    
    Show-PodeWebTableColumn -Name <string> -Key <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Key <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Show-PodeWebToast
    
SYNTAX
    Show-PodeWebToast [-Message] <string> [[-Title] <string>] [[-Duration] <int>] [[-Icon] <string>]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Duration <int>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Message <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Start-PodeWebAudio
    
SYNTAX
    Start-PodeWebAudio -Id <string>  [<CommonParameters>]
    
    Start-PodeWebAudio -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Start-PodeWebFileStream
    
SYNTAX
    Start-PodeWebFileStream -Id <string>  [<CommonParameters>]
    
    Start-PodeWebFileStream -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Start-PodeWebVideo
    
SYNTAX
    Start-PodeWebVideo -Id <string>  [<CommonParameters>]
    
    Start-PodeWebVideo -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Stop-PodeWebAudio
    
SYNTAX
    Stop-PodeWebAudio -Id <string>  [<CommonParameters>]
    
    Stop-PodeWebAudio -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Stop-PodeWebFileStream
    
SYNTAX
    Stop-PodeWebFileStream -Id <string>  [<CommonParameters>]
    
    Stop-PodeWebFileStream -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Stop-PodeWebVideo
    
SYNTAX
    Stop-PodeWebVideo -Id <string>  [<CommonParameters>]
    
    Stop-PodeWebVideo -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Submit-PodeWebForm
    
SYNTAX
    Submit-PodeWebForm -Name <string>  [<CommonParameters>]
    
    Submit-PodeWebForm -Id <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Sync-PodeWebChart
    
SYNTAX
    Sync-PodeWebChart -Id <string>  [<CommonParameters>]
    
    Sync-PodeWebChart -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Sync-PodeWebSelect
    
SYNTAX
    Sync-PodeWebSelect -Name <string>  [<CommonParameters>]
    
    Sync-PodeWebSelect -Id <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Sync-PodeWebTable
    
SYNTAX
    Sync-PodeWebTable -Id <string>  [<CommonParameters>]
    
    Sync-PodeWebTable -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Sync-PodeWebTile
    
SYNTAX
    Sync-PodeWebTile -Id <string>  [<CommonParameters>]
    
    Sync-PodeWebTile -Name <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Test-PodeWebPage
    
SYNTAX
    Test-PodeWebPage [-Name] <string> [[-Group] <string>] [-NoGroup]  [<CommonParameters>]
    
    
PARAMETERS
    -Group <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoGroup
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Test-PodeWebTheme
    
SYNTAX
    Test-PodeWebTheme [[-Name] <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Name <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebAudio
    
SYNTAX
    Update-PodeWebAudio -Id <string> [-Source <hashtable[]>] [-Track <hashtable[]>]  [<CommonParameters>]
    
    Update-PodeWebAudio -Name <string> [-Source <hashtable[]>] [-Track <hashtable[]>]  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Source <hashtable[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Track <hashtable[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebBadge
    
SYNTAX
    Update-PodeWebBadge [-Id] <string> [[-Value] <string>] [[-Colour] { | Blue | Grey | Green | Red | Yellow 
    | Cyan | Light | Dark}]  [<CommonParameters>]
    
    
PARAMETERS
    -Colour <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebButton
    
SYNTAX
    Update-PodeWebButton -Id <string> [-DisplayName <string>] [-Icon <string>] [-Colour { | Blue | Grey | 
    Green | Red | Yellow | Cyan | Light | Dark}] [-ColourState {Unchanged | Outline | Solid}] [-Size { | 
    Normal | Small | Large}] [-SizeState {Unchanged | Normal | Full}]  [<CommonParameters>]
    
    Update-PodeWebButton -Name <string> [-DisplayName <string>] [-Icon <string>] [-Colour { | Blue | Grey | 
    Green | Red | Yellow | Cyan | Light | Dark}] [-ColourState {Unchanged | Outline | Solid}] [-Size { | 
    Normal | Small | Large}] [-SizeState {Unchanged | Normal | Full}]  [<CommonParameters>]
    
    
PARAMETERS
    -Colour <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -ColourState <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DisplayName <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Icon <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Size <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -SizeState <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebChart
    
SYNTAX
    Update-PodeWebChart -Data <Object> -Name <string>  [<CommonParameters>]
    
    Update-PodeWebChart -Data <Object> -Id <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Data <Object>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Object
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebCheckbox
    
SYNTAX
    Update-PodeWebCheckbox -Id <string> [-OptionId <int>] [-State {Unchanged | Disabled | Enabled}] 
    [-Checked]  [<CommonParameters>]
    
    Update-PodeWebCheckbox -Name <string> [-OptionId <int>] [-State {Unchanged | Disabled | Enabled}] 
    [-Checked]  [<CommonParameters>]
    
    
PARAMETERS
    -Checked
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -OptionId <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -State <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebCodeEditor
    
SYNTAX
    Update-PodeWebCodeEditor -Id <string> [-Value <string>] [-Language <string>]  [<CommonParameters>]
    
    Update-PodeWebCodeEditor -Name <string> [-Value <string>] [-Language <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Language <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebFileStream
    
SYNTAX
    Update-PodeWebFileStream -Id <string> [-Url <string>]  [<CommonParameters>]
    
    Update-PodeWebFileStream -Name <string> [-Url <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebIFrame
    
SYNTAX
    Update-PodeWebIFrame -Id <string> [-Url <string>] [-Title <string>]  [<CommonParameters>]
    
    Update-PodeWebIFrame -Name <string> [-Url <string>] [-Title <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Url <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebProgress
    
SYNTAX
    Update-PodeWebProgress -Name <string> [-Value <int>] [-Colour { | Blue | Grey | Green | Red | Yellow | 
    Cyan | Light | Dark}]  [<CommonParameters>]
    
    Update-PodeWebProgress -Id <string> [-Value <int>] [-Colour { | Blue | Grey | Green | Red | Yellow | Cyan 
    | Light | Dark}]  [<CommonParameters>]
    
    
PARAMETERS
    -Colour <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Value <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebSelect
    
SYNTAX
    Update-PodeWebSelect -Name <string> -Options <string[]> [-DisplayOptions <string[]>] [-SelectedValue 
    <string[]>]  [<CommonParameters>]
    
    Update-PodeWebSelect -Id <string> -Options <string[]> [-DisplayOptions <string[]>] [-SelectedValue 
    <string[]>]  [<CommonParameters>]
    
    
PARAMETERS
    -DisplayOptions <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Options <string[]>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -SelectedValue <string[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.String[]
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebTable
    
SYNTAX
    Update-PodeWebTable -Data <Object> -Id <string> [-Columns <hashtable[]>] [-Paginate] [-PageIndex <int>] 
    [-TotalItemCount <int>] [-Force]  [<CommonParameters>]
    
    Update-PodeWebTable -Data <Object> -Name <string> [-Columns <hashtable[]>] [-Paginate] [-PageIndex <int>] 
    [-TotalItemCount <int>] [-Force]  [<CommonParameters>]
    
    
PARAMETERS
    -Columns <hashtable[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Data <Object>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Force
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -PageIndex <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Paginate
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -TotalItemCount <int>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Object
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebTableRow
    
SYNTAX
    Update-PodeWebTableRow -Name <string> -DataValue <string> [-Data <Object>] [-BackgroundColour <string>] 
    [-Colour <string>]  [<CommonParameters>]
    
    Update-PodeWebTableRow -Id <string> -Index <int> [-Data <Object>] [-BackgroundColour <string>] [-Colour 
    <string>]  [<CommonParameters>]
    
    Update-PodeWebTableRow -Id <string> -DataValue <string> [-Data <Object>] [-BackgroundColour <string>] 
    [-Colour <string>]  [<CommonParameters>]
    
    Update-PodeWebTableRow -Name <string> -Index <int> [-Data <Object>] [-BackgroundColour <string>] [-Colour 
    <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -BackgroundColour <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Colour <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Data <Object>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -DataValue <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name_and_DataValue, ID_and_DataValue
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           ID_and_Index, ID_and_DataValue
        Aliases                      None
        Dynamic?                     false
        
    -Index <int>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name_and_Index, ID_and_Index
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name_and_Index, Name_and_DataValue
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Object
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebText
    
SYNTAX
    Update-PodeWebText [-Id] <string> [-Value] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    true
        Position?                    1
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.String
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebTextbox
    
SYNTAX
    Update-PodeWebTextbox -Value <Object> -Name <string> [-AsJson] [-Multiline]  [<CommonParameters>]
    
    Update-PodeWebTextbox -Value <Object> -Id <string> [-AsJson] [-Multiline]  [<CommonParameters>]
    
    
PARAMETERS
    -AsJson
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Multiline
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Value <Object>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      Data
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.Object
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebTheme
    
SYNTAX
    Update-PodeWebTheme [-Name] <string>  [<CommonParameters>]
    
    
PARAMETERS
    -Name <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebTile
    
SYNTAX
    Update-PodeWebTile -Id <string> [-Value <string>] [-Colour { | Blue | Grey | Green | Red | Yellow | Cyan 
    | Light | Dark}]  [<CommonParameters>]
    
    Update-PodeWebTile -Name <string> [-Value <string>] [-Colour { | Blue | Grey | Green | Red | Yellow | 
    Cyan | Light | Dark}]  [<CommonParameters>]
    
    
PARAMETERS
    -Colour <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Value <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       true (ByValue)
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    System.String
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Update-PodeWebVideo
    
SYNTAX
    Update-PodeWebVideo -Id <string> [-Source <hashtable[]>] [-Track <hashtable[]>] [-Thumbnail <string>]  
    [<CommonParameters>]
    
    Update-PodeWebVideo -Name <string> [-Source <hashtable[]>] [-Track <hashtable[]>] [-Thumbnail <string>]  
    [<CommonParameters>]
    
    
PARAMETERS
    -Id <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Id
        Aliases                      None
        Dynamic?                     false
        
    -Name <string>
        
        Required?                    true
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           Name
        Aliases                      None
        Dynamic?                     false
        
    -Source <hashtable[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Thumbnail <string>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Track <hashtable[]>
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Use-PodeWebPages
    
SYNTAX
    Use-PodeWebPages [[-Path] <string>]  [<CommonParameters>]
    
    
PARAMETERS
    -Path <string>
        
        Required?                    false
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None





NAME
    Use-PodeWebTemplates
    
SYNTAX
    Use-PodeWebTemplates [-Title] <string> [[-Logo] <string>] [[-FavIcon] <string>] [[-Theme] {Auto | Light | 
    Dark | Terminal | Custom}] [[-EndpointName] <string[]>] [[-Security] {None | Default | Simple | Strict}] 
    [-NoPageFilter] [-HideSidebar] [-UseHsts]  [<CommonParameters>]
    
    
PARAMETERS
    -EndpointName <string[]>
        
        Required?                    false
        Position?                    4
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -FavIcon <string>
        
        Required?                    false
        Position?                    2
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -HideSidebar
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Logo <string>
        
        Required?                    false
        Position?                    1
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -NoPageFilter
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Security <string>
        
        Required?                    false
        Position?                    5
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Theme <string>
        
        Required?                    false
        Position?                    3
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -Title <string>
        
        Required?                    true
        Position?                    0
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    -UseHsts
        
        Required?                    false
        Position?                    Named
        Accept pipeline input?       false
        Parameter set name           (All)
        Aliases                      None
        Dynamic?                     false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see 
        about_CommonParameters (https:/go.microsoft.com/fwlink/?LinkID=113216). 
    
    
INPUTS
    None
    
    
OUTPUTS
    System.Object
    
ALIASES
    None
    

REMARKS
    None




