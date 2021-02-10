# API-Automated-Testing-Postman

Postman makes it easy to work with APIs and perform exploratory testing.
Instead of creating calls manually to send over the command line, all you need is a Postman Collection. Import a collection directly in JSON format.

Parameterize your requests:
Use our built-in library of dynamic variables to generate dynamic dummy data for testing multiple iterations of the same request with different values.

Inspect responses of any size:
View the status code, response time, and response size. Postman's automatic language detection, link and syntax highlighting, search, and text formatting options make it easy to inspect the response body.

Use scripts to send asynchronous requests:
Use pre-request scripts to execute logic in the background when sending multiple requests. Instead of waiting for a call to complete and blocking further requests, designate a callback function and you'll be notified when it's done.

Chain requests to create test scenarios:
Chain requests to create test suites by using pre-request and test scripts to parse information from the response body and save it as a variable used in additional requests.

Easily share your findings:
Document your discoveries in a collection and communicate them to developers by sharing the collection to a team workspace.

**Sample API specification:**

<table>
<thead>
<tr>
<th align="left">endpoints</th>
<th align="left">description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>GET: /api/add?value1=8&value2=4.2</code></td>
<td align="left">returns a sum of passed values</td>
</tr>
<tr>
<td align="left"><code>GET: /api/validate?value=123</code></td>
<td align="left">validates passed parameter and returns type</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Expected result</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>empty String ("")</code></td>
<td align="left">returns null</td>
</tr>
  <tr>
<td align="left"><code>Integer > 10000</code></td>
<td align="left">returns big Integer</td>
</tr>
  <tr>
<td align="left"><code>Integer < 10000 </code></td>
<td align="left">returns small Integer</td>
</tr>
  <tr>
<td align="left"><code>String with lenght > 20</code></td>
<td align="left">return very long String</td>
</tr>
  <tr>
<td align="left"><code>String with 11 < length < 20 </code></td>
<td align="left">returns medium String</td>
</tr>
  <tr>
<td align="left"><code>String with 4 < length < 10</code></td>
<td align="left">returns small String</td>
</tr>
  <tr>
<td align="left"><code>String with lenght < 3</code></td>
<td align="left">returns very short String</td>
</tr>

Explaratory testing plan, test collections and test runs for given API can be found above.
