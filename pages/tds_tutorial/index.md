---
title: TDS Online Tutorial
last_updated: 2016-09-26
summary: "TDS Tutorial outline"
sidebar: tdsTutorial_sidebar 
permalink: tds_tutorial_index.html
toc: false
---

# THREDDS Data Server Administration Tutorial

{::comment}

This text is completely ignored by kramdown - a comment in the text.
## TDS Overview (link:TDSOverview.pptx[ppt])
(link:TDSOverview.pdf[pdf])

## 1.Tomcat Configuration

* <<GettingStarted#,Getting Started With the TDS: Local Test
Server Setup>>
* <<Security#,Security Overview>>

## 2. TDS Configuration

* <<CatalogPrimer#,Client Catalog Primer>>
* <<BasicConfigCatalogs#,Basic TDS Configuration Catalogs>>
* <<ConfigCatalogs#,TDS Configuration Catalogs>>
* <<BasicThreddsConfig_xml#,Basic threddsConfig.xml>>
* <<AddingServices#,Adding OGC/ISO Services>>
* <<../reference/WMS#,Detailed WMS Configuration>>
* Netcdf Subset Service:
<<../reference/NetcdfSubsetServiceConfigure#,configure>>,
<<../reference/NetcdfSubsetServiceReference#,reference>>
* threddsConfig.xml
<<../reference/ThreddsConfigXMLFile#,reference>>

## 4. TDS Monitoring and Debugging

* <<TDSMonitoringAndDebugging#,TDS Monitoring and Debugging>>
* <<TomcatAndTDSLogs#,Tomcat and TDS Logs>>
* <<tdsMonitor#,Using the TdsMonitor tool>>
* There are also various free, 3rd-party monitoring and debugging tools:
** http://www.google.com/search?btnG#1&pws#0&q#log+analyzers[Log
analyzers]
** http://tomcat.apache.org/tomcat-7.0-doc/manager-howto.html[Tomcat
manager application]
** Browser-based HTTP header viewers
*** http://www.youtube.com/watch?v#tKD50_zvZoo[Live HTTP Headers]
(Firefox Add-On)
*** https://developers.google.com/chrome-developer-tools/docs/network#http_headers[DevTools]
(Chrome)
** JVM monitoring tools
*** http://visualvm.java.net/api-quickstart.html[VisualVM]
*** http://www.youtube.com/watch?v#Xy0tsT-GD68[JConsole]

## 5. Using NcML in TDS

* <<../../netcdf-java/ncml/Tutorial#,Basic NcML tutorial>>
* <<../../netcdf-java/ncml/Aggregation#,NcML Aggregation>>
* <<NcML#,Using NcML in the TDS>>
* <<NcMLExamples#,NcML Example Problems>>
* <<NcMLAggExamples#,NcML Aggregation Example Problems>>

## 6. Feature Collections

* <<../reference/collections/FeatureCollections#,Feature
Collections>>
* <<../reference/collections/GribCollections#,GRIB Feature
Collections>>
* <<GRIBFeatureCollectionTutorial#,GRIB Feature Collection
Tutorial>>
* <<../reference/collections/FmrcCollection#,FMRC (Forecast Model
Run Collections)>>]
* <<FmrcFeatureCollectionsTutorial#,FMRC Tutorial>>
* <<../../netcdf-java/reference/formats/GribFiles#,GRIB Files in
CDM>>
* <<../../netcdf-java/reference/formats/GribTables#,GRIB Tables
in CDM>>]

## 7. Other Advanced Features

* <<../reference/RestrictedAccess#,Restricting dataset access>>
* <<../reference/Viewers#,Viewer Links>>

## 8. Metadata

* <<Metadata#,THREDDS Metadata>>
* <<../reference/ncISO#,ISO metadata generation: (ncIso)>>

## 9. Production Servers

* <<Checklist#,Installation Checklist for Production>>
* <<TroubleShooting#,TroubleShooting Problems>>
* <<../reference/Performance#,Performance
Tips TroubleShooting>>
* <<../UpgradingTo4.5#,Upgrading to 4.5>>

## Other Resources:

* <<../reference/index#,Reference documentation>>
* <<../faq#,FAQ>>

{:/comment}
