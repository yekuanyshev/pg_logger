# pg_logger
postgres logger trigger function

## Usage
```sql
CREATE TRIGGER <trigger_name>
AFTER INSERT OR UPDATE OR DELETE
ON <table_name>
FOR EACH ROW
EXECUTE PROCEDURE logger();
```