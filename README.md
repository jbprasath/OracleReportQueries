# OracleReportQueries
Oracle Report Queries 

1. Export to CSV With Header
    As SYS user:

    CREATE OR REPLACE DIRECTORY TEST_DIR AS '\tmp\myfiles'
    /
    GRANT READ, WRITE ON DIRECTORY TEST_DIR TO myuser
    /
    As user:
