# JavaScript Export to Excel

#### Resources used:
- [DataTables.net](https://datatables.net/)
- [Bootstrap Elements](https://www.w3schools.com/bootstrap/bootstrap_get_started.asp)

## Integration
### 1. Include these two files :

```js
import cdn.datatables.net/1.10.20/css/jquery.dataTables.min.css
import cdn.datatables.net/1.10.20/js/jquery.dataTables.min.js
```

### 2. Call this JS function :

```js
// called when DOM document (page) is loaded
$(document).ready( function () {
    $('#myTable').DataTable();
} );
```
