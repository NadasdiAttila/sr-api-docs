# API Status Codes

### 2xx Success

<table>
<tr>
<th>Code</th>
<th>Text</th>
<th>Details</th>
</tr> 
<tr>
<td>200</td>
<td>OK</td>
<td>The request was successfully processed by ShopRenter</td>
</tr>
<tr>
<td>201</td>
<td>Created</td>
<td>The request has been successfully processed by ShopRenter, and a resource has been created.</td>
</tr>
<tr>
<td>204</td>
<td>No Content</td>
<td>The request has been successfully processed by ShopRenter, and there is no content to return.</td>
</tr>
</table>

### 4xx Client error

<table>
<tr>
<th>Code</th>
<th>InnerCode</th>
<th>Text</th>
</tr> 
<tr>
<td>400</td>
<td>40001</td>
<td>Data parameter not found in POST/PUT!</td>
</tr>
<tr>
<td>400</td>
<td>40002</td>
<td>The following fields are readonly: {field}!</td>
</tr>
<tr>
<td>400</td>
<td>40003</td>
<td>The following fields are required: {field}!</td>
</tr>
<tr>
<td>400</td>
<td>40004</td>
<td>The following query parameters are required: {field}!</td>
</tr>
<tr>
<td>400</td>
<td>40005</td>
<td>The given data is wrong!</td>
</tr>
<tr>
<td>400</td>
<td>40005</td>
<td>The {field} field cannot be empty</td>
</tr>  
<tr>
<td>400</td>
<td>40005</td>
<td>The given data is empty or not in PHP array format.</td>
</tr>
<tr>
<td>400</td>
<td>40005</td>
<td>The {parameter} parameter is an already exist OuterID.</td>
</tr>
<tr>
<td>400</td>
<td>40005</td>
<td>The {parameter} must be integer 1 between 1000000000.</td>
</tr>  
<tr>
<td>400</td>
<td>40005</td>
<td>The {parameter} parameter has wrong data. The data is not int.</td>
</tr>
<tr>
<td>400</td>
<td>40005</td>
<td>The {parameter} parameter has wrong data. The data is not scalar (scalar is integer, float, string or boolean).</td>
</tr>
<tr>
<td>400</td>
<td>40005</td>
<td>The {parameter} parameter has wrong data. Can not add CustomerGroupPrice to the Default CustomerGroup.</td>
</tr>
<tr>
<td>400</td>
<td>40005</td>
<td>The {parameter} parameter has wrong data. This parameter is enum type. Check API documentation for accepted values.</td>
</tr>
<tr>
<td>400</td>
<td>40005</td>
<td>The {parameter} parameter is not a valid resource identifier or invalid format. Valid format: array([id] => dGF4Q2xhc3MtdGF4X2NsYXNzX2lkPTEw)</td>
</tr>
<tr>
<td>400</td>
<td>40006</td>
<td>Some resource identity in the given data is wrong!</td>
</tr>
<tr>
<td>400</td>
<td>40007</td>
<td>The given resource id is wrong: {id}!</td>
</tr>
<tr>
<td>400</td>
<td>40007</td>
<td>The given OuterId is not exist: {id}!</td>
</tr>
<tr>
<td>400</td>
<td>40008</td>
<td>Page not found! This Resource minimum page is 0 and maximum page is {page}</td>
</tr>
<tr>
<td>400</td>
<td>40009</td>
<td>The given datetime parameter: {parameter} is invalid! Valid datetime format is 1990-01-01T00:00:00</td>
</tr>
<tr>
<td>400</td>
<td>40010</td>
<td>The given parameter: {parameter} is not available!</td>
</tr>
<tr>
<td>400</td>
<td>40011</td>
<td>Resource identity is missing.</td>
</tr>
<tr>
<td>400</td>
<td>40012</td>
<td>Product does not have product class!</td>
</tr>
<tr>
<td>400</td>
<td>40013</td>
<td>POST content length exceeds the limit of {limit} bytes.</td>
</tr>
<tr>
<td>400</td>
<td>40014</td>
<td>POST is either empty or content length exceeds the limit of {limit} bytes.</td>
</tr>
<tr>
<td>400</td>
<td>40015</td>
<td>Reached maximum product limit.</td>
</tr>
<tr>
<td>400</td>
<td>40016</td>
<td>The {parameter} parameter is not UTF-8 encoded.</td>
</tr>
<tr>
<td>400</td>
<td>40017</td>
<td>The given date parameter: {parameter} is invalid! Valid date format is 1990-01-01</td>
</tr>
<tr>
<td>400</td>
<td>40018</td>
<td>Reached maximum attribute limit. The limit is {limit}</td>
</tr>
<tr>
<td>400</td>
<td>40021</td>
<td>Both variant parameters cannot reference the same attribute!</td>
</tr>
<tr>
<td>400</td>
<td>40022</td>
<td>Text attribute cannot be used as variant parameter</td>
</tr>
<tr>
<td>400</td>
<td>40023</td>
<td>Only list attributes can have ICON select type</td>
</tr>
<tr>
<td>400</td>
<td>40024</td>
<td>Another product class with the same name already exists!</td>
</tr>
<tr>
<td>400</td>
<td>40025</td>
<td>Cannot delete product class which has products!</td>
</tr>
<tr>
<td>400</td>
<td>40032</td>
<td>The given orderBy parameter: {parameter} is invalid!</td>
</tr>
<tr>
<td>401</td>
<td>40101</td>
<td>You have no permission for this operation!</td>
</tr>
<tr>
<td>404</td>
<td>40033</td>
<td>Product not found with sku: {parameter}</td>
</tr>
<tr>
<td>404</td>
<td>40401</td>
<td>Resource not found! {resource}</td>
</tr>
<tr>
<td>403</td>
<td>-</td>
<td>Forbidden</td>
</tr>
<tr>
<td>409</td>
<td>40901</td>
<td>Resource exists!</td>
</tr>
<tr>
<td>429</td>
<td>-</td>
<td>Too Many Requests</td>
</tr>
</table>

### 5xx Success

<table>
<tr>
<th>Code</th>
<th>Text</th>
<th>Details</th>
</tr>
<tr>
<td>500</td>
<td>Internal Server Error</td>
<td>When an error has occurred within the API.</td>
</tr>
<tr>
<td>503</td>
<td>Service Unavailable</td>
<td>The server is currently unavailable.</td>
</tr>
<tr>
<td>504</td>
<td>Gateway Timeout</td>
<td>The request could not complete in time. Try breaking it down in multiple smaller requests.</td>
</tr>
</table>
