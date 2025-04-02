# Spotfire

<?xml version="1.0" encoding="utf-8"?>
<as:Job xmlns:as="urn:tibco:spotfire.dxp.automation">
  <as:Tasks>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"111926"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"111926"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"111926"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"111926"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"111926"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\SINBON ELECTRONICS_111926_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\SINBON ELECTRONICS_111926_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\SINBON ELECTRONICS_111926_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\SINBON ELECTRONICS_111926_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\SINBON ELECTRONICS_111926_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\SINBON ELECTRONICS_111926_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\SINBON ELECTRONICS_111926_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113657"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113657"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113657"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113657"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113657"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Prodrive Technologies Suzhou_113657_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Prodrive Technologies Suzhou_113657_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Prodrive Technologies Suzhou_113657_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Prodrive Technologies Suzhou_113657_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Prodrive Technologies Suzhou_113657_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Prodrive Technologies Suzhou_113657_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Prodrive Technologies Suzhou_113657_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113760"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113760"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113760"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113760"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113760"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\KMWE Malaysia_113760_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\KMWE Malaysia_113760_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\KMWE Malaysia_113760_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\KMWE Malaysia_113760_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\KMWE Malaysia_113760_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\KMWE Malaysia_113760_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\KMWE Malaysia_113760_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113662"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113662"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113662"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113662"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113662"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Benchmark Electronics (M) SDN BHD_113662_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Benchmark Electronics (M) SDN BHD_113662_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Benchmark Electronics (M) SDN BHD_113662_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Benchmark Electronics (M) SDN BHD_113662_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Benchmark Electronics (M) SDN BHD_113662_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Benchmark Electronics (M) SDN BHD_113662_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Benchmark Electronics (M) SDN BHD_113662_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"114039"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"114039"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"114039"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"114039"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"114039"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Molliturn_114039_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Molliturn_114039_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Molliturn_114039_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Molliturn_114039_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Molliturn_114039_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Molliturn_114039_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Molliturn_114039_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"114022"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"114022"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"114022"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"114022"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"114022"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Toray Precision_114022_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Toray Precision_114022_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Toray Precision_114022_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Toray Precision_114022_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Toray Precision_114022_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Toray Precision_114022_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Toray Precision_114022_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"110951"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"110951"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"110951"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"110951"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"110951"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\BLIKSEN_110951_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\BLIKSEN_110951_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\BLIKSEN_110951_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\BLIKSEN_110951_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\BLIKSEN_110951_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\BLIKSEN_110951_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\BLIKSEN_110951_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"110740"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"110740"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"110740"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"110740"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"110740"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Precision Engineering Co., Ltd(PE Tech)_110740_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Precision Engineering Co., Ltd(PE Tech)_110740_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Precision Engineering Co., Ltd(PE Tech)_110740_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Precision Engineering Co., Ltd(PE Tech)_110740_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Precision Engineering Co., Ltd(PE Tech)_110740_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Precision Engineering Co., Ltd(PE Tech)_110740_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Precision Engineering Co., Ltd(PE Tech)_110740_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"101422"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"101422"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"101422"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"101422"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"101422"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP(MIC M3 EUR)_101422_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP(MIC M3 EUR)_101422_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP(MIC M3 EUR)_101422_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP(MIC M3 EUR)_101422_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP(MIC M3 EUR)_101422_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP(MIC M3 EUR)_101422_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\MARKETECH INTERNATIONAL CORP(MIC M3 EUR)_101422_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"109159"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"109159"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"109159"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"109159"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"109159"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Dee Hon LTD_109159_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Dee Hon LTD_109159_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Dee Hon LTD_109159_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Dee Hon LTD_109159_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Dee Hon LTD_109159_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Dee Hon LTD_109159_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Dee Hon LTD_109159_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"102531"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"102531"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"102531"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"102531"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"102531"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\DELTA ELECTRONICS_102531_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\DELTA ELECTRONICS_102531_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\DELTA ELECTRONICS_102531_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\DELTA ELECTRONICS_102531_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\DELTA ELECTRONICS_102531_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\DELTA ELECTRONICS_102531_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\DELTA ELECTRONICS_102531_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"117086"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"117086"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"117086"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"117086"});
SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"117086"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\AMAX INFORMATION TECHNOLOGIES CO.,LTD (AMAX TW)_117086_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\AMAX INFORMATION TECHNOLOGIES CO.,LTD (AMAX TW)_117086_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\AMAX INFORMATION TECHNOLOGIES CO.,LTD (AMAX TW)_117086_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\AMAX INFORMATION TECHNOLOGIES CO.,LTD (AMAX TW)_117086_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\AMAX INFORMATION TECHNOLOGIES CO.,LTD (AMAX TW)_117086_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\AMAX INFORMATION TECHNOLOGIES CO.,LTD (AMAX TW)_117086_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\AMAX INFORMATION TECHNOLOGIES CO.,LTD (AMAX TW)_117086_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"107312"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"107312"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"107312"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"107312"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"107312"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\RORZE TECHNOLOGY INCORPORATION_107312_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\RORZE TECHNOLOGY INCORPORATION_107312_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\RORZE TECHNOLOGY INCORPORATION_107312_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\RORZE TECHNOLOGY INCORPORATION_107312_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\RORZE TECHNOLOGY INCORPORATION_107312_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\RORZE TECHNOLOGY INCORPORATION_107312_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\RORZE TECHNOLOGY INCORPORATION_107312_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113143"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113143"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113143"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113143"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113143"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Kyocera Asia Pacific_113143_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Kyocera Asia Pacific_113143_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Kyocera Asia Pacific_113143_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Kyocera Asia Pacific_113143_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Kyocera Asia Pacific_113143_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Kyocera Asia Pacific_113143_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Kyocera Asia Pacific_113143_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"112188"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"112188"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"112188"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"112188"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"112188"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Tailyn Technologies_112188_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Tailyn Technologies_112188_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Tailyn Technologies_112188_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Tailyn Technologies_112188_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Tailyn Technologies_112188_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Tailyn Technologies_112188_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Tailyn Technologies_112188_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113504"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113504"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113504"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113504"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113504"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\SUPER MICRO COMPUTER_113504_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\SUPER MICRO COMPUTER_113504_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\SUPER MICRO COMPUTER_113504_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\SUPER MICRO COMPUTER_113504_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\SUPER MICRO COMPUTER_113504_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\SUPER MICRO COMPUTER_113504_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\SUPER MICRO COMPUTER_113504_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"112522"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"112522"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"112522"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"112522"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"112522"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP BRANC_112522_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP BRANC_112522_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP BRANC_112522_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP BRANC_112522_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP BRANC_112522_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\MARKETECH INTERNATIONAL CORP BRANC_112522_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\MARKETECH INTERNATIONAL CORP BRANC_102522_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"102448"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"102448"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"102448"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"102448"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"102448"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Gongin Precision_102448_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Gongin Precision_102448_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Gongin Precision_102448_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Gongin Precision_102448_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Gongin Precision_102448_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Gongin Precision_102448_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Gongin Precision_102448_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"102202"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"102202"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"102202"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"102202"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"102202"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\ZHU XING PRECISE INDUSTRIAL_102202_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\ZHU XING PRECISE INDUSTRIAL_102202_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\ZHU XING PRECISE INDUSTRIAL_102202_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\ZHU XING PRECISE INDUSTRIAL_102202_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\ZHU XING PRECISE INDUSTRIAL_102202_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\ZHU XING PRECISE INDUSTRIAL_102202_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\ZHU XING PRECISE INDUSTRIAL_102202_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"105469"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"105469"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"105469"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"105469"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"105469"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\WAVE POWER TECHNOLOGY_105469_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\WAVE POWER TECHNOLOGY_105469_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\WAVE POWER TECHNOLOGY_105469_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\WAVE POWER TECHNOLOGY_105469_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\WAVE POWER TECHNOLOGY_105469_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\WAVE POWER TECHNOLOGY_105469_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\WAVE POWER TECHNOLOGY_105469_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"102284"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"102284"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"102284"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"102284"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"102284"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\ZENTI SHEET METAL TECHNICAL_102284_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\ZENTI SHEET METAL TECHNICAL_102284_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\ZENTI SHEET METAL TECHNICAL_102284_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\ZENTI SHEET METAL TECHNICAL_102284_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\ZENTI SHEET METAL TECHNICAL_102284_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\ZENTI SHEET METAL TECHNICAL_102284_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\ZENTI SHEET METAL TECHNICAL_102284_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113189"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113189"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113189"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113189"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113189"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\SCHNEEBERGER AG LINEARTECHNIK_113189_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\SCHNEEBERGER AG LINEARTECHNIK_113189_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\SCHNEEBERGER AG LINEARTECHNIK_113189_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\SCHNEEBERGER AG LINEARTECHNIK_113189_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\SCHNEEBERGER AG LINEARTECHNIK_113189_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\SCHNEEBERGER AG LINEARTECHNIK_113189_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\SCHNEEBERGER AG LINEARTECHNIK_113189_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"107716"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"107716"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"107716"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"107716"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"107716"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\HO SONG ENTERPRISE_107716_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\HO SONG ENTERPRISE_107716_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\HO SONG ENTERPRISE_107716_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\HO SONG ENTERPRISE_107716_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\HO SONG ENTERPRISE_107716_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\HO SONG ENTERPRISE_107716_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\HO SONG ENTERPRISE_107716_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"102097"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"102097"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"102097"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"102097"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"102097"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Feedback Technology_102097_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Feedback Technology_102097_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Feedback Technology_102097_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Feedback Technology_102097_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Feedback Technology_102097_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Feedback Technology_102097_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Feedback Technology_102097_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"112245"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"112245"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"112245"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"112245"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"112245"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\TAINAN QUANTUM TECHNOLOGIES_112245_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\TAINAN QUANTUM TECHNOLOGIES_112245_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\TAINAN QUANTUM TECHNOLOGIES_112245_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\TAINAN QUANTUM TECHNOLOGIES_112245_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\TAINAN QUANTUM TECHNOLOGIES_112245_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\TAINAN QUANTUM TECHNOLOGIES_112245_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\TAINAN QUANTUM TECHNOLOGIES_112245_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"107886"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"107886"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"107886"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"107886"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"107886"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Beijing Jinjiguang Co LTD_107886_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Beijing Jinjiguang Co LTD_107886_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Beijing Jinjiguang Co LTD_107886_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Beijing Jinjiguang Co LTD_107886_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Beijing Jinjiguang Co LTD_107886_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Beijing Jinjiguang Co LTD_107886_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Beijing Jinjiguang Co LTD_107886_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"105892"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"105892"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"105892"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"105892"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"105892"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\SUN VAC TECHNOLOGY_105892_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\SUN VAC TECHNOLOGY_105892_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\SUN VAC TECHNOLOGY_105892_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\SUN VAC TECHNOLOGY_105892_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\SUN VAC TECHNOLOGY_105892_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\SUN VAC TECHNOLOGY_105892_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\SUN VAC TECHNOLOGY_105892_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"107521"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"107521"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"107521"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"107521"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"107521"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\CHYUAN WAY PRECISION_107521_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\CHYUAN WAY PRECISION_107521_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\CHYUAN WAY PRECISION_107521_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\CHYUAN WAY PRECISION_107521_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\CHYUAN WAY PRECISION_107521_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\CHYUAN WAY PRECISION_107521_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\CHYUAN WAY PRECISION_107521_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"105135"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"105135"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"105135"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"105135"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"105135"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\BROOKS AUTOMATION_105135_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\BROOKS AUTOMATION_105135_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\BROOKS AUTOMATION_105135_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\BROOKS AUTOMATION_105135_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\BROOKS AUTOMATION_105135_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\BROOKS AUTOMATION_105135_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\BROOKS AUTOMATION_105135_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"115103"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"115103"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"115103"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"115103"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"115103"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\CCI CHUN INTERNATIONAL CO., LTD._115103_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\CCI CHUN INTERNATIONAL CO., LTD._115103_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\CCI CHUN INTERNATIONAL CO., LTD._115103_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\CCI CHUN INTERNATIONAL CO., LTD._115103_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\CCI CHUN INTERNATIONAL CO., LTD._115103_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\CCI CHUN INTERNATIONAL CO., LTD._115103_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\CCI CHUN INTERNATIONAL CO., LTD._115103_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"109575"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"109575"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"109575"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"109575"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"109575"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\AVEX-SG Technology Inc.(AVEX)_109575_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\AVEX-SG Technology Inc.(AVEX)_109575_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\AVEX-SG Technology Inc.(AVEX)_109575_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\AVEX-SG Technology Inc.(AVEX)_109575_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\AVEX-SG Technology Inc.(AVEX)_109575_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\AVEX-SG Technology Inc.(AVEX)_109575_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\AVEX-SG Technology Inc.(AVEX)_109575_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"109069"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"109069"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"109069"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"109069"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"109069"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\BISON ADVANCED TECHNOLOGY CO., LTD.(BISON)_109069_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\BISON ADVANCED TECHNOLOGY CO., LTD.(BISON)_109069_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\BISON ADVANCED TECHNOLOGY CO., LTD.(BISON)_109069_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\BISON ADVANCED TECHNOLOGY CO., LTD.(BISON)_109069_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\BISON ADVANCED TECHNOLOGY CO., LTD.(BISON)_109069_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\BISON ADVANCED TECHNOLOGY CO., LTD.(BISON)_109069_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\BISON ADVANCED TECHNOLOGY CO., LTD.(BISON)_109069_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"110936"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"110936"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"110936"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"110936"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"110936"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\SEMCO TECHNOLOGIES(SEMCO-France)_110936_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\SEMCO TECHNOLOGIES(SEMCO-France)_110936_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\SEMCO TECHNOLOGIES(SEMCO-France)_110936_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\SEMCO TECHNOLOGIES(SEMCO-France)_110936_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\SEMCO TECHNOLOGIES(SEMCO-France)_110936_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\SEMCO TECHNOLOGIES(SEMCO-France)_110936_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\SEMCO TECHNOLOGIES(SEMCO-France)_110936_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113651"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113651"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113651"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113651"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113651"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Zollner Electronic(Taicang) Co.,Ltd_113651_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Zollner Electronic(Taicang) Co.,Ltd_113651_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Zollner Electronic(Taicang) Co.,Ltd_113651_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Zollner Electronic(Taicang) Co.,Ltd_113651_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Zollner Electronic(Taicang) Co.,Ltd_113651_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Zollner Electronic(Taicang) Co.,Ltd_113651_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Zollner Electronic(Taicang) Co.,Ltd_113651_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"114416"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"114416"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"114416"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"114416"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"114416"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\KONZERN LASER PRECISION CO., LTD(KONZERN)_114416_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\KONZERN LASER PRECISION CO., LTD(KONZERN)_114416_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\KONZERN LASER PRECISION CO., LTD(KONZERN)_114416_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\KONZERN LASER PRECISION CO., LTD(KONZERN)_114416_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\KONZERN LASER PRECISION CO., LTD(KONZERN)_114416_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\KONZERN LASER PRECISION CO., LTD(KONZERN)_114416_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\KONZERN LASER PRECISION CO., LTD(KONZERN)_114416_1_MQP30_Data</FilePath>
    </ExportDataToFile>
    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"109888"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"109888"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"109888"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"109888"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"109888"});
</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\EMMT SYSTEMS CORPORATION(EMMT)_109888_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\EMMT SYSTEMS CORPORATION(EMMT)_109888_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\EMMT SYSTEMS CORPORATION(EMMT)_109888_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\EMMT SYSTEMS CORPORATION(EMMT)_109888_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\EMMT SYSTEMS CORPORATION(EMMT)_109888_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\EMMT SYSTEMS CORPORATION(EMMT)_109888_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\EMMT SYSTEMS CORPORATION(EMMT)_109888_1_MQP30_Data</FilePath>
    </ExportDataToFile>

<OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"102416"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"102416"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"102416"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"102416"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"102416"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\Agilent Technologies.(Agilent TW)_102416_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\Agilent Technologies.(Agilent TW)_102416_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\Agilent Technologies.(Agilent TW)_102416_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\Agilent Technologies.(Agilent TW)_102416_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\Agilent Technologies.(Agilent TW)_102416_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\Agilent Technologies.(Agilent TW)_102416_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\Agilent Technologies.(Agilent TW)_102416_1_MQP30_Data</FilePath>
    </ExportDataToFile>


    <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113538"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113538"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113538"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113538"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113538"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\HQ PACK SDN BHD_113538_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\ HQ PACK SDN BHD_113538_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\ HQ PACK SDN BHD_113538_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\HQ PACK SDN BHD_113538_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\HQ PACK SDN BHD_113538_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\HQ PACK SDN BHD_113538_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\HQ PACK SDN BHD_113538_1_MQP30_Data</FilePath>
    </ExportDataToFile>

<OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"112136"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"112136"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"112136"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"112136"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"112136"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\LIMO SYSTEM TECHNOLOGY CO., LTD.(LMYTEC)_112136_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\LIMO SYSTEM TECHNOLOGY CO., LTD.(LMYTEC)_112136_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\LIMO SYSTEM TECHNOLOGY CO., LTD.(LMYTEC)_112136_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\LIMO SYSTEM TECHNOLOGY CO., LTD.(LMYTEC)_112136_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\LIMO SYSTEM TECHNOLOGY CO., LTD.(LMYTEC)_112136_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\LIMO SYSTEM TECHNOLOGY CO., LTD.(LMYTEC)_112136_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\LIMO SYSTEM TECHNOLOGY CO., LTD.(LMYTEC)_112136_1_MQP30_Data</FilePath>
    </ExportDataToFile>


<OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"113738"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"113738"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"113738"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"113738"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"113738"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\TAIWAN FYLIN INDUSTRIAL CO., LTD._113738_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\TAIWAN FYLIN INDUSTRIAL CO., LTD._113738_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\TAIWAN FYLIN INDUSTRIAL CO., LTD._113738_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\TAIWAN FYLIN INDUSTRIAL CO., LTD._113738_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\TAIWAN FYLIN INDUSTRIAL CO., LTD._113738_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\TAIWAN FYLIN INDUSTRIAL CO., LTD._113738_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\TAIWAN FYLIN INDUSTRIAL CO., LTD._113738_1_MQP30_Data</FilePath>
    </ExportDataToFile>


<OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"108191"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"102416"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"108191"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"108191"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"108191"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\TransPak Taiwan.(TransPak)_108191_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\TransPak Taiwan.(TransPak)_108191_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\TransPak Taiwan.(TransPak)_108191_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\TransPak Taiwan.(TransPak)_108191_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\TransPak Taiwan.(TransPak)_108191_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\TransPak Taiwan.(TransPak)_108191_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\TransPak Taiwan.(TransPak)_108191_1_MQP30_Data</FilePath>
    </ExportDataToFile>



  <OpenAnalysisFromLibrary xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Open Analysis from Library</as:Title>
      <AnalysisPath>/OPERATIONS/Supply Chain Management/SNM/Supplier SNM Dashboard</AnalysisPath>
      <ConfigurationBlock>SetFilter(tableName="Suppliers",columnName="Vendor Code",values={"111255"});
SetFilter(tableName="MQP_Supplier",columnName="VENDOR_CODE",values={"102416"});SetFilter(tableName="HMI_SPF_OTIF_V",columnName="VENDOR",values={"111255"});SetFilter(tableName="SV_MN_MQP",columnName="Vendor Code",values={"111255"});SetFilter(tableName="SV_MN_RCA",columnName="SUPPLIER",values={"111255"});</ConfigurationBlock>
    </OpenAnalysisFromLibrary>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a8b78235-2407-4ca6-986f-44c0c59248c1</VisualizationId>
      <DestinationPath>C:\Localdata\TOUCH-DOWN TECHNOLOGY CO., LTD.(Touchdown)_108191_1_MQP30_Overall.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>e36a0f42-93e7-40cd-955b-185e9b0ce0d2</VisualizationId>
      <DestinationPath>C:\Localdata\TOUCH-DOWN TECHNOLOGY CO., LTD.(Touchdown)_108191_1_MQP30_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>957130e7-28b7-4d0f-ac48-045957c5a267</VisualizationId>
      <DestinationPath>C:\Localdata\TOUCH-DOWN TECHNOLOGY CO., LTD.(Touchdown)_108191_3_OTIF_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>a31357d4-91ea-40be-a970-a51ae539f739</VisualizationId>
      <DestinationPath>C:\Localdata\TOUCH-DOWN TECHNOLOGY CO., LTD.(Touchdown)_108191_3_OTIF_Breakdown.png</DestinationPath>
      <Width>1400</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>f1e8f2e9-8aea-407c-8489-5ed414d7e56b</VisualizationId>
      <DestinationPath>C:\Localdata\TOUCH-DOWN TECHNOLOGY CO., LTD.(Touchdown)_108191_1_RCA CT_Performance.png</DestinationPath>
      <Width>1400</Width>
      <Height>548</Height>
    </ExportImage>
    <ExportImage xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Image</as:Title>
      <VisualizationId>b7685cc6-0bb9-4a0c-8d63-07e5222e76f8</VisualizationId>
      <DestinationPath>C:\Localdata\TOUCH-DOWN TECHNOLOGY CO., LTD.(Touchdown)_108191_1_RCA CT_Data.png</DestinationPath>
      <Width>1800</Width>
      <Height>250</Height>
    </ExportImage>
    <ExportDataToFile xmlns="urn:tibco:spotfire.dxp.automation.tasks">
      <as:Title>Export Data to File</as:Title>
      <ExportTableVisualization>true</ExportTableVisualization>
      <DataTableId>00000000-0000-0000-0000-000000000000</DataTableId>
      <VisualizationId>189ed2d5-dce2-4574-a5dc-66cad36aa305</VisualizationId>
      <VisualizationName>Report - MQP 3.0 - MN Data</VisualizationName>
      <ExportFormatName>Spotfire.ExcelXlsxDataWriter</ExportFormatName>
      <ExportFormatDisplayName>Microsoft Excel Workbooks: *.xlsx</ExportFormatDisplayName>
      <FilePath>C:\Localdata\TOUCH-DOWN TECHNOLOGY CO., LTD.(Touchdown)_108191_1_MQP30_Data</FilePath>
    </ExportDataToFile>









  </as:Tasks>
</as:Job>
