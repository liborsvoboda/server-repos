﻿<pre class="csharp" style="font-family:monospace;">    <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">partial</span> <span style="color: #6666cc; font-weight: bold;">class</span> ServerConfigSettings <span style="color: #008000;">{</span>

        <span style="color: #008080;">#region Emailer Service</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Service email, for info about not available service from HeatchCheck Can be used for</span>
        <span style="color: #008080; font-style: italic;">/// next Develop, automatic checking problems, missing data and all other Its Necessary for</span>
        <span style="color: #008080; font-style: italic;">/// Correct running Server Internal Core Monitoring</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> EmailerServiceEmailAddress <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"Libor.Svoboda@GroupWare-Solution.Eu"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// SMTP Server Address for Login to External Mail Server Its Necessary for Correct running</span>
        <span style="color: #008080; font-style: italic;">/// Server Internal Core Monitoring</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> EmailerSMTPServerAddress <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"imap.groupware-solution.eu"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// SMTP Port for Login to External Mail Server Its Necessary for Correct running Server</span>
        <span style="color: #008080; font-style: italic;">/// Internal Core Monitoring</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">int</span> EmailerSMTPPort <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #FF0000;">25</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// EmailerSMTPSslIsEnabled SSl Email Protocol for Login to External Mail Server Its</span>
        <span style="color: #008080; font-style: italic;">/// Necessary for Correct running Server Internal Core Monitoring</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> EmailerSMTPSslIsEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">false</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// SMTP UserName for Login to External Mail Server Its Necessary for Correct running Server</span>
        <span style="color: #008080; font-style: italic;">/// Internal Core Monitoring</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> EmailerSMTPLoginUsername <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"backendsolution@groupware-solution.eu"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// SMTP Password for Login to External Mail Server Its Necessary for Correct running Server</span>
        <span style="color: #008080; font-style: italic;">/// Internal Core Monitoring</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> EmailerSMTPLoginPassword <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"password"</span><span style="color: #008000;">;</span>

        <span style="color: #008080;">#endregion Emailer Service</span>

        <span style="color: #008080;">#region Server Database</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Server Database Connection string for Full Service of Database</span>
        <span style="color: #008080; font-style: italic;">/// Migration/Api/Check/Unlimited Develop !!!Warning: Check this connection for</span>
        <span style="color: #008080; font-style: italic;">/// Read/Write/Exec is enabled</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> DatabaseConnectionString <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"Server=127.0.0.1;Database=EASYDATACenter;Trusted_Connection=True;TrustServerCertificate=True"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable Disable Entity Framework Internal Cache I recommend turning it off : from Logic,</span>
        <span style="color: #008080; font-style: italic;">/// Duplicit Functionality with Database Server in complex process can generate problems</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: false</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #6666cc; font-weight: bold;">bool</span> DatabaseInternalCachingEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">false</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Time in Minutes for Database Valid Cache Data and Refreshing Duplicit Functionality with</span>
        <span style="color: #008080; font-style: italic;">/// Database Server</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: 30</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #6666cc; font-weight: bold;">int</span> DatabaseInternalCacheTimeoutMin <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #FF0000;">30</span><span style="color: #008000;">;</span>

        <span style="color: #008080;">#endregion Server Database</span>

        <span style="color: #008080;">#region Server Future Technologies</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Server Service Name automatic figured in All IS/OS/Engines info</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: EASYDATACenter</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> SpecialServerServiceName <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"EASYDATACenter"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// User Web Root Path for Startup</span> 
        <span style="color: #008080; font-style: italic;">/// and Any missing address Automatic Redirection</span>
        <span style="color: #008080; font-style: italic;">/// Not need Regex Configuration</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #6666cc; font-weight: bold;">string</span> SpecialUserWebRootPath <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"/Dashboard"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Activation / Deactivation of Email Sender For Server Core Fails Checker All Catch Write</span>
        <span style="color: #008080; font-style: italic;">/// to SendEmail, In Debug mode is Written in console in Release mode is Sended email (All</span>
        <span style="color: #008080; font-style: italic;">/// incorrect server statuses are monitored) Can be writen to Database - !!! Warning for</span>
        <span style="color: #008080; font-style: italic;">/// infinite Cycling (DB shutdown example)</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: true</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> SpecialCoreCheckerEmailSenderActive <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">false</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Special Function: Using Selected Tables with AutoRefresh On change as Local DataSets,</span>
        <span style="color: #008080; font-style: italic;">/// For Optimize Traffic. For Example LanguageList - Static table with often reading</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: true - functionality must be implemented in Server Code</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> SpecialUseDbLocalAutoupdatedDials <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">false</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Server Language for Translating Server internal statuses</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: cz or en - other languages are not implemented</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> SpecialServerLanguage <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"cz"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Server support mass emailing as Service</span>
        <span style="color: #008080; font-style: italic;">/// You can enable Mass Email Api</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> SpecialEnableMassEmail <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080;">#endregion Server Future Technologies</span>

        <span style="color: #008080;">#region ServerConfigurationServices</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Set Server Startup Port on Http/HttpS/WebSocket and for All Engines, Modules, API</span>
        <span style="color: #008080; font-style: italic;">/// Controler and WebPages</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: 5000</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">int</span> ConfigServerStartupPort <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #FF0000;">5000</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// WebSocket Timeout Connection Settings in Minutes. After timeout when not detected any</span>
        <span style="color: #008080; font-style: italic;">/// communication socket is closed Set according to your need</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: 2</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">double</span> ConfigWebSocketTimeoutMin <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #FF0000;">2</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Maximum socket message size for control Traffic</span>
        <span style="color: #008080; font-style: italic;">/// Recomended: 10</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">int</span> ConfigMaxWebSocketBufferSizeKb <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #FF0000;">10</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Bearer Token Timeout Setting in Minutes. Connection must be Refreshed in Interval After</span>
        <span style="color: #008080; font-style: italic;">/// Timeout connection Must Login Again. It is as needed. You Can Change Key for close All</span>
        <span style="color: #008080; font-style: italic;">/// connections Immediately. Timeout is good for Webpages</span>
        <span style="color: #008080; font-style: italic;">/// Recomended: 15</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">double</span> ConfigApiTokenTimeoutMin <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #FF0000;">15</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Setting for Server URL Services. Logically can run only one Http or Https Server has</span>
        <span style="color: #008080; font-style: italic;">/// more Security Setting Politics.</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: true</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ConfigServerStartupOnHttps <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Setting for Automatic Obtain Lets Encrypt</span>
        <span style="color: #008080; font-style: italic;">/// more Security Setting Politics.</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: true</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ConfigServerGetLetsEncrypt <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">false</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Its Domain for include to Automatic Generated Certificate For Server running on HTTPS.</span>
        <span style="color: #008080; font-style: italic;">/// Domain is for Your validation Certificate Domain. Can be Changed for commercial.</span>
        <span style="color: #008080; font-style: italic;">/// Domain is Used for Lets Encrypt also</span>
        <span style="color: #008080; font-style: italic;">/// Write with Comma separator</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: 127.0.0.1</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> ConfigCertificateDomain <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"127.0.0.1"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Password will be inserted to Server Generated Certificate for HTTPS.</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: empty = Maximal Security Randomly generated 20 chars string</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> ConfigCertificatePassword <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> ServerCoreFunctions<span style="color: #008000;">.</span><span style="color: #0000FF;">RandomString</span><span style="color: #008000;">(</span><span style="color: #FF0000;">20</span><span style="color: #008000;">)</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Special Functions:Server AutoGenerated encryption Key For Securing Communication On Each</span>
        <span style="color: #008080; font-style: italic;">/// Server Restart All Tokens not will be valid and the Login Reconnect is Requested. Its</span>
        <span style="color: #008080; font-style: italic;">/// AntiHacker Security Rule</span>
        <span style="color: #008080; font-style: italic;">/// Recommended: empty = Maximal Security Randomly generated 40 chars string</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> ConfigJwtLocalKey <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> ServerCoreFunctions<span style="color: #008000;">.</span><span style="color: #0000FF;">RandomString</span><span style="color: #008000;">(</span><span style="color: #FF0000;">40</span><span style="color: #008000;">)</span><span style="color: #008000;">;</span>

        <span style="color: #008080;">#endregion ServerConfigurationServices</span>

        <span style="color: #008080;">#region Server Engines</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable Disable Bearer Token Timeout Validation Token can be valid EveryTime to using:</span>
        <span style="color: #008080; font-style: italic;">/// Example for machine connection Or is Control last activity</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerTimeTokenValidationEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">false</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable Razor WebPages support engine with Correct Configuration for Automaping form</span>
        <span style="color: #008080; font-style: italic;">/// folder 'Pages'</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerRazorWebPagesEngineEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable Mvc WebPages support engine with Correct Configuration</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerMvcWebPagesEngineEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable JS WebPages support engine with Correct Configuration</span>
        <span style="color: #008080; font-style: italic;">/// React, Nodejs, etc..</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerJsWebPagesEngineEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">false</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Definition of WebPage Startup npmscript command</span>
        <span style="color: #008080; font-style: italic;">/// React, Nodejs, etc..</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">string</span> ServerJsWebStartupCommand <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #666666;">"start"</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable WebSocket Engine with Default Example Api Controller</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerWebSocketEngineEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable FTP File Server oppened for every connection with full rights</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerFtpEngineEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable FTP Security</span>
        <span style="color: #008080; font-style: italic;">/// For access to FTP must be logged</span> 
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerFtpSecurityEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable WebPages File Browsing from server Url on Server</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerWebBrowserEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Server support online multi watch Logging</span>
        <span style="color: #008080; font-style: italic;">/// Its Run on Websocket and the Log Messages are</span>
        <span style="color: #008080; font-style: italic;">/// sent for All opened connections for wathing</span>
        <span style="color: #008080; font-style: italic;">/// on Path: ServerCoreMonitor</span>
        <span style="color: #008080; font-style: italic;">/// You can enable Mass Email Api</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ServerEnableWebSocketMonitor <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080;">#endregion Server Engines</span>

        <span style="color: #008080;">#region Server Modules</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Special Function: Server Automatically Generate Full Documentation of API structure AND</span>
        <span style="color: #008080; font-style: italic;">/// Database Model. Plus Included API Interface for Online Testing All API Methods with</span>
        <span style="color: #008080; font-style: italic;">/// Authentication Its Automatic Solution for Third Party cooperation. All changes are</span>
        <span style="color: #008080; font-style: italic;">/// Reflected after restart server</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ModuleSwaggerApiDocEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Special Function: AutoGenerated Database DataManager for working with Data Running only</span>
        <span style="color: #008080; font-style: italic;">/// in Debug mode for simple Develop, can be modified. All changes are Reflected after</span>
        <span style="color: #008080; font-style: italic;">/// restart server</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ModuleDataManagerEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Special Function: More than 200 Server Statuses Can be monitored by HeathCheckService,</span>
        <span style="color: #008080; font-style: italic;">/// Over Net can Control Other Company Services Also as Central Control Point With Email</span>
        <span style="color: #008080; font-style: italic;">/// Service. For Example: Server/Memory/All DB Types/IP/HDD/Port/Api/NET/Cloud/Environment</span>
        <span style="color: #008080; font-style: italic;">/// Must be run for Metrics AddOn https://learn.microsoft.com/en-us/dotnet/architecture/microservices/implement-resilient-applications/monitor-app-health</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ModuleHealthServiceEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Special Function: More than 200 Server Statuses Can be monitored by HeathCheckService,</span>
        <span style="color: #008080; font-style: italic;">/// Over Net can Control Other Company Services Also as Central Control Point With Email</span>
        <span style="color: #008080; font-style: italic;">/// Service. For Example: Server/Memory/All DB Types/IP/HDD/Port/Api/NET/Cloud/Environment</span>
        <span style="color: #008080; font-style: italic;">/// Must be run for Metrics AddOn !!! run in Release mode for Good Reading of Logs without</span>
        <span style="color: #008080; font-style: italic;">/// HeathChecks Cycling info https://github.com/Xabaril/AspNetCore.Diagnostics.HealthChecks https://testfully.io/blog/api-health-check-monitoring/</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">int</span> ModuleHealthServiceRefreshIntervalSec <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #FF0000;">30</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable Server Structure Documentation for Developers Using RootPath, - Block File</span>
        <span style="color: #008080; font-style: italic;">/// Browsing Is Good for Server with Documentation only Or Use for Show WebPage and Copy</span>
        <span style="color: #008080; font-style: italic;">/// "Only HTML"</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ModuleMdDocumentationEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span>

        <span style="color: #008080; font-style: italic;">/// <summary>
        <span style="color: #008080; font-style: italic;">/// Enable Automatic Database Diagram for Simple show Database structure with All bingings</span>
        <span style="color: #008080; font-style: italic;">///</span> </summary></span>
        <span style="color: #0600FF; font-weight: bold;">public</span> <span style="color: #0600FF; font-weight: bold;">static</span> <span style="color: #6666cc; font-weight: bold;">bool</span> ModuleDbDiagramGeneratorEnabled <span style="color: #008000;">{</span> <span style="color: #0600FF; font-weight: bold;">get</span><span style="color: #008000;">;</span> <span style="color: #0600FF; font-weight: bold;">set</span><span style="color: #008000;">;</span> <span style="color: #008000;">}</span> <span style="color: #008000;">=</span> <span style="color: #0600FF; font-weight: bold;">true</span><span style="color: #008000;">;</span></pre>