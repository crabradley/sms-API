# sms-API
&lt;!DOCTYPE html> &lt;html lang="en"> &lt;head>      &lt;meta charset="utf-8">     &lt;title>ClientConfigBuilder - Documentation&lt;/title>       &lt;script src="scripts/prettify/prettify.js">&lt;/script>     &lt;script src="scripts/prettify/lang-css.js">&lt;/script>     &lt;!--[if lt IE 9]>       &lt;script src="//html5shiv.googlecode.com/svn/trunk/html5.js">&lt;/script>     &lt;![endif]-->     &lt;link type="text/css" rel="stylesheet" href="styles/prettify.css">     &lt;link type="text/css" rel="stylesheet" href="styles/jsdoc.css">     &lt;script src="scripts/nav.js" defer>&lt;/script>     &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"> &lt;/head> &lt;body>  &lt;input type="checkbox" id="nav-trigger" class="nav-trigger" /> &lt;label for="nav-trigger" class="navicon-button x">   &lt;div class="navicon">&lt;/div> &lt;/label>  &lt;label for="nav-trigger" class="overlay">&lt;/label>  &lt;nav class="wrap">      &lt;input type="text" id="nav-search" placeholder="Search" />      &lt;h2>&lt;a href="index.html">Home&lt;/a>&lt;/h2>&lt;h3>Modules&lt;/h3>&lt;ul>&lt;li>&lt;a href="module-PDFToolsSDK.html">PDFToolsSDK&lt;/a>&lt;/li>&lt;/ul>&lt;h3>Classes&lt;/h3>&lt;ul>&lt;li>&lt;a href="ExecutionContext.html">ExecutionContext&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ExecutionContext.html#.create">create&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ClientConfig.html">ClientConfig&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ClientConfig.html#.clientConfigBuilder">clientConfigBuilder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ClientConfigBuilder.html">ClientConfigBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ClientConfigBuilder.html#withConnectTimeout">withConnectTimeout&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ClientConfigBuilder.html#withReadTimeout">withReadTimeout&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ClientConfigBuilder.html#fromFile">fromFile&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ClientConfigBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="FileRef.html">FileRef&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="FileRef.html#.createFromLocalFile">createFromLocalFile&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="FileRef.html#.createFromStream">createFromStream&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="FileRef.html#saveAsFile">saveAsFile&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="FileRef.html#writeToStream">writeToStream&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="Credentials.html">Credentials&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="Credentials.html#.serviceAccountCredentialsBuilder">serviceAccountCredentialsBuilder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ServiceAccountCredentialsBuilder.html">ServiceAccountCredentialsBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentialsBuilder.html#withClientId">withClientId&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentialsBuilder.html#withClientSecret">withClientSecret&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentialsBuilder.html#withPrivateKey">withPrivateKey&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentialsBuilder.html#withOrganizationId">withOrganizationId&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentialsBuilder.html#withAccountId">withAccountId&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentialsBuilder.html#fromFile">fromFile&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentialsBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ServiceAccountCredentials.html">ServiceAccountCredentials&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentials.html#getClientId">getClientId&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentials.html#getClientSecret">getClientSecret&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentials.html#getPrivateKey">getPrivateKey&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentials.html#getOrganizationId">getOrganizationId&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceAccountCredentials.html#getAccountId">getAccountId&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CombineFilesOperation.html">CombineFilesOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CombineFilesOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CombineFilesOperation.html#addInput">addInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CombineFilesOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CompressPDFOperation.html">CompressPDFOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CompressPDFOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CompressPDFOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CompressPDFOperation.html#setOptions">setOptions&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CompressPDFOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFOperation.html">CreatePDFOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFOperation.html#setOptions">setOptions&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="DeletePagesOperation.html">DeletePagesOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="DeletePagesOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="DeletePagesOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="DeletePagesOperation.html#setPageRanges">setPageRanges&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="DeletePagesOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="DocumentMergeOperation.html">DocumentMergeOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="DocumentMergeOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="DocumentMergeOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="DocumentMergeOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ExportPDFOperation.html">ExportPDFOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ExportPDFOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ExportPDFOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ExportPDFOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="InsertPagesOperation.html">InsertPagesOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="InsertPagesOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="InsertPagesOperation.html#setBaseInput">setBaseInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="InsertPagesOperation.html#addPagesToInsertAt">addPagesToInsertAt&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="InsertPagesOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="LinearizePDFOperation.html">LinearizePDFOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="LinearizePDFOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="LinearizePDFOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="LinearizePDFOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="OCROperation.html">OCROperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="OCROperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="OCROperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="OCROperation.html#setOptions">setOptions&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="OCROperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CompressPDFOptions.html">CompressPDFOptions&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CompressPDFOptions.html#.Builder">Builder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CompressPDFOptionsBuilder.html">CompressPDFOptionsBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CompressPDFOptionsBuilder.html#withCompressionLevel">withCompressionLevel&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CompressPDFOptionsBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFFromExcelOptions.html">CreatePDFFromExcelOptions&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromExcelOptions.html#.Builder">Builder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFFromExcelOptionsBuilder.html">CreatePDFFromExcelOptionsBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromExcelOptionsBuilder.html#withDocumentLanguage">withDocumentLanguage&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromExcelOptionsBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFFromHtmlOptions.html">CreatePDFFromHtmlOptions&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromHtmlOptions.html#.Builder">Builder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFFromHtmlOptionsBuilder.html">CreatePDFFromHtmlOptionsBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromHtmlOptionsBuilder.html#includesHeaderFooter">includesHeaderFooter&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromHtmlOptionsBuilder.html#withPageLayout">withPageLayout&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromHtmlOptionsBuilder.html#withDataToMerge">withDataToMerge&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromHtmlOptionsBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFFromPPTOptions.html">CreatePDFFromPPTOptions&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromPPTOptions.html#.Builder">Builder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFFromPPTOptionsBuilder.html">CreatePDFFromPPTOptionsBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromPPTOptionsBuilder.html#withDocumentLanguage">withDocumentLanguage&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromPPTOptionsBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFFromWordOptions.html">CreatePDFFromWordOptions&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromWordOptions.html#.Builder">Builder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="CreatePDFFromWordOptionsBuilder.html">CreatePDFFromWordOptionsBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromWordOptionsBuilder.html#withDocumentLanguage">withDocumentLanguage&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="CreatePDFFromWordOptionsBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="PageLayout.html">PageLayout&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="PageLayout.html#setPageSize">setPageSize&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="DocumentMergeOptions.html">DocumentMergeOptions&lt;/a>&lt;/li>&lt;li>&lt;a href="OCROptions.html">OCROptions&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="OCROptions.html#.Builder">Builder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="OCROptionsBuilder.html">OCROptionsBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="OCROptionsBuilder.html#withOcrType">withOcrType&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="OCROptionsBuilder.html#withOcrLang">withOcrLang&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="OCROptionsBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="PageRanges.html">PageRanges&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="PageRanges.html#addSinglePage">addSinglePage&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="PageRanges.html#addPageRange">addPageRange&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="PageRanges.html#addAllFrom">addAllFrom&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="PageRanges.html#addAll">addAll&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="PasswordProtectOptions.html">PasswordProtectOptions&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="PasswordProtectOptions.html#.Builder">Builder&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="PasswordProtectOptionsBuilder.html">PasswordProtectOptionsBuilder&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="PasswordProtectOptionsBuilder.html#setUserPassword">setUserPassword&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="PasswordProtectOptionsBuilder.html#setOwnerPassword">setOwnerPassword&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="PasswordProtectOptionsBuilder.html#setEncryptionAlgorithm">setEncryptionAlgorithm&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="PasswordProtectOptionsBuilder.html#setContentEncryption">setContentEncryption&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="PasswordProtectOptionsBuilder.html#setPermissions">setPermissions&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="PasswordProtectOptionsBuilder.html#build">build&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="Permissions.html">Permissions&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="Permissions.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="Permissions.html#getValues">getValues&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="Permissions.html#addPermission">addPermission&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ProtectPDFOperation.html">ProtectPDFOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ProtectPDFOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ProtectPDFOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ProtectPDFOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="RemoveProtectionOperation.html">RemoveProtectionOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="RemoveProtectionOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="RemoveProtectionOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="RemoveProtectionOperation.html#setPassword">setPassword&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="RemoveProtectionOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ReorderPagesOperation.html">ReorderPagesOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ReorderPagesOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ReorderPagesOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ReorderPagesOperation.html#setPagesOrder">setPagesOrder&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ReorderPagesOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ReplacePagesOperation.html">ReplacePagesOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ReplacePagesOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ReplacePagesOperation.html#setBaseInput">setBaseInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ReplacePagesOperation.html#addPagesForReplace">addPagesForReplace&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ReplacePagesOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="RotatePagesOperation.html">RotatePagesOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="RotatePagesOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="RotatePagesOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="RotatePagesOperation.html#setAngleToRotatePagesBy">setAngleToRotatePagesBy&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="RotatePagesOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="SplitPDFOperation.html">SplitPDFOperation&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="SplitPDFOperation.html#.createNew">createNew&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="SplitPDFOperation.html#setInput">setInput&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="SplitPDFOperation.html#setPageRanges">setPageRanges&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="SplitPDFOperation.html#setFileCount">setFileCount&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="SplitPDFOperation.html#setPageCount">setPageCount&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="SplitPDFOperation.html#execute">execute&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ServiceApiError.html">ServiceApiError&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceApiError.html#getStatusCode">getStatusCode&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceApiError.html#getErrorCode">getErrorCode&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceApiError.html#getMessage">getMessage&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceApiError.html#getRequestTrackingId">getRequestTrackingId&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceApiError.html#toString">toString&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;li>&lt;a href="ServiceUsageError.html">ServiceUsageError&lt;/a>&lt;ul class='methods'>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceUsageError.html#getStatusCode">getStatusCode&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceUsageError.html#getErrorCode">getErrorCode&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceUsageError.html#getMessage">getMessage&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceUsageError.html#getRequestTrackingId">getRequestTrackingId&lt;/a>&lt;/li>&lt;li data-type='method' style='display: none;'>&lt;a href="ServiceUsageError.html#toString">toString&lt;/a>&lt;/li>&lt;/ul>&lt;/li>&lt;/ul> &lt;/nav>  &lt;div id="main">      &lt;h1 class="page-title">ClientConfigBuilder&lt;/h1>        &lt;section>  &lt;header>          &lt;h2>         ClientConfigBuilder         &lt;/h2>              &lt;div class="class-description">&lt;p>Builds a &lt;a href="ClientConfig.html">ClientConfig&lt;/a> instance.&lt;/p>&lt;/div>   &lt;/header>  &lt;article>                          &lt;h3 class="subsection-title">Methods&lt;/h3>           &lt;h4 class="name" id="withConnectTimeout">&lt;span class="type-signature">&lt;/span>withConnectTimeout&lt;span class="signature">(connectTimeout&lt;span class="signature-attributes">non-null&lt;/span>)&lt;/span>&lt;span class="type-signature"> &amp;rarr; {&lt;a href="ClientConfigBuilder.html">ClientConfigBuilder&lt;/a>}&lt;/span>&lt;/h4>       &lt;dl class="details">                                 &lt;/dl>      &lt;div class="description">     &lt;p>Sets the connect timeout. It should be greater than zero.&lt;/p> &lt;/div>                &lt;h5>Parameters:&lt;/h5>   &lt;table class="params">     &lt;thead>     &lt;tr>          &lt;th>Name&lt;/th>           &lt;th>Type&lt;/th>              &lt;th class="last">Description&lt;/th>     &lt;/tr>     &lt;/thead>      &lt;tbody>           &lt;tr>                  &lt;td class="name">&lt;code>connectTimeout&lt;/code>&lt;/td>               &lt;td class="type">   &lt;span class="param-type">Number&lt;/span>                &lt;/td>                  &lt;td class="description last">&lt;p>Determines the timeout in milliseconds until a connection is established in the API calls. Default value is 10000 milliseconds&lt;/p>&lt;/td>         &lt;/tr>       &lt;/tbody> &lt;/table>                 &lt;h5>Returns:&lt;/h5>   &lt;div class="param-desc">     &lt;p>This Builder instance to add any additional parameters.&lt;/p> &lt;/div>    &lt;dl class="param-type">     &lt;dt>         Type     &lt;/dt>     &lt;dd>  &lt;span class="param-type">&lt;a href="ClientConfigBuilder.html">ClientConfigBuilder&lt;/a>&lt;/span>       &lt;/dd> &lt;/dl>               &lt;h4 class="name" id="withReadTimeout">&lt;span class="type-signature">&lt;/span>withReadTimeout&lt;span class="signature">(readTimeout&lt;span class="signature-attributes">non-null&lt;/span>)&lt;/span>&lt;span class="type-signature"> &amp;rarr; {&lt;a href="ClientConfigBuilder.html">ClientConfigBuilder&lt;/a>}&lt;/span>&lt;/h4>       &lt;dl class="details">                                 &lt;/dl>      &lt;div class="description">     &lt;p>Sets the read timeout. It should be greater than zero.&lt;/p> &lt;/div>                &lt;h5>Parameters:&lt;/h5>   &lt;table class="params">     &lt;thead>     &lt;tr>          &lt;th>Name&lt;/th>           &lt;th>Type&lt;/th>              &lt;th class="last">Description&lt;/th>     &lt;/tr>     &lt;/thead>      &lt;tbody>           &lt;tr>                  &lt;td class="name">&lt;code>readTimeout&lt;/code>&lt;/td>               &lt;td class="type">   &lt;span class="param-type">Number&lt;/span>                &lt;/td>                  &lt;td class="description last">&lt;p>Defines the read timeout in milliseconds, which is the timeout for waiting for data or, put differently, a maximum period inactivity between two consecutive data packets. Default value is 10000 milliseconds&lt;/p>&lt;/td>         &lt;/tr>       &lt;/tbody> &lt;/table>                 &lt;h5>Returns:&lt;/h5>   &lt;div class="param-desc">     &lt;p>This Builder instance to add any additional parameters.&lt;/p> &lt;/div>    &lt;dl class="param-type">     &lt;dt>         Type     &lt;/dt>     &lt;dd>  &lt;span class="param-type">&lt;a href="ClientConfigBuilder.html">ClientConfigBuilder&lt;/a>&lt;/span>       &lt;/dd> &lt;/dl>               &lt;h4 class="name" id="fromFile">&lt;span class="type-signature">&lt;/span>fromFile&lt;span class="signature">(clientConfigFilePath&lt;span class="signature-attributes">non-null&lt;/span>)&lt;/span>&lt;span class="type-signature"> &amp;rarr; {&lt;a href="ClientConfigBuilder.html">ClientConfigBuilder&lt;/a>}&lt;/span>&lt;/h4>       &lt;dl class="details">                                 &lt;/dl>      &lt;div class="description">     &lt;p>Sets the connect timeout and read timeout using the JSON client config file path. All the keys in the JSON structure are optional.&lt;/p> &lt;p> JSON structure: &lt;pre> {   "connectTimeout": "4000",   "readTimeout": "20000" } &lt;/pre> &lt;/div>                &lt;h5>Parameters:&lt;/h5>   &lt;table class="params">     &lt;thead>     &lt;tr>          &lt;th>Name&lt;/th>           &lt;th>Type&lt;/th>              &lt;th class="last">Description&lt;/th>     &lt;/tr>     &lt;/thead>      &lt;tbody>           &lt;tr>                  &lt;td class="name">&lt;code>clientConfigFilePath&lt;/code>&lt;/td>               &lt;td class="type">   &lt;span class="param-type">String&lt;/span>                &lt;/td>                  &lt;td class="description last">&lt;p>JSON client config file path&lt;/p>&lt;/td>         &lt;/tr>       &lt;/tbody> &lt;/table>                 &lt;h5>Returns:&lt;/h5>   &lt;div class="param-desc">     &lt;p>This Builder instance to add any additional parameters.&lt;/p> &lt;/div>    &lt;dl class="param-type">     &lt;dt>         Type     &lt;/dt>     &lt;dd>  &lt;span class="param-type">&lt;a href="ClientConfigBuilder.html">ClientConfigBuilder&lt;/a>&lt;/span>       &lt;/dd> &lt;/dl>               &lt;h4 class="name" id="build">&lt;span class="type-signature">&lt;/span>build&lt;span class="signature">()&lt;/span>&lt;span class="type-signature"> &amp;rarr; {&lt;a href="ClientConfig.html">ClientConfig&lt;/a>}&lt;/span>&lt;/h4>       &lt;dl class="details">                                 &lt;/dl>      &lt;div class="description">     &lt;p>Returns a new &lt;a href="ClientConfig.html">ClientConfig&lt;/a> instance built from the current state of this builder.&lt;/p> &lt;/div>                          &lt;h5>Returns:&lt;/h5>   &lt;div class="param-desc">     &lt;p>A ClientConfig instance.&lt;/p> &lt;/div>    &lt;dl class="param-type">     &lt;dt>         Type     &lt;/dt>     &lt;dd>  &lt;span class="param-type">&lt;a href="ClientConfig.html">ClientConfig&lt;/a>&lt;/span>       &lt;/dd> &lt;/dl>            &lt;/article>  &lt;/section>       &lt;/div>  &lt;br class="clear">  &lt;footer>     Documentation generated by &lt;a href="https://github.com/jsdoc3/jsdoc">JSDoc 3.6.3&lt;/a> using the &lt;a href="https://github.com/clenemt/docdash">docdash&lt;/a> theme. &lt;/footer>  &lt;script>prettyPrint();&lt;/script> &lt;script src="scripts/polyfill.js">&lt;/script> &lt;script src="scripts/linenumber.js">&lt;/script>  &lt;script src="scripts/search.js" defer>&lt;/script>   &lt;script src="scripts/collapse.js" defer>&lt;/script>       &lt;link type="text/css" rel="stylesheet" href="custom.css">  &lt;/body> &lt;/html> 
