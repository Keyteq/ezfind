Important notice regarding performance logging
==============================================


This branch of ezfind has been enhanced to report perf metrics using ezperformancelogger.

The code is pretty safe to use, as it checks for existence of the eZPerfLogger class before using it,
but in case you want to revert the changes, the modified files are:
. ezsolr.php
. ezsolrbase.php
