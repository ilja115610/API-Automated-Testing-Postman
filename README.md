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

<table>
<thead>
<tr>
<th align="left">resource</th>
<th align="left">description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>/api/forecasts/places</code></td>
<td align="left">returns a list of places</td>
</tr>
<tr>
<td align="left"><code>/api/forecasts/places/temperature</code></td>
<td align="left">returns a list of places, filtered by temperature</td>
</tr>
<tr>
<td align="left"><code>/api/forecasts/places/winds</code></td>
<td align="left">returns a list of places, filtered by winds</td>
</tr>
<tr>
<td align="left"><code>/api/forecasts/phenomenon-types</code></td>
<td align="left">returns a list of phenomenon types</td>
</tr>
<tr>
<td align="left"><code>/api/forecasts/time-of-day-types</code></td>
<td align="left">returns a list of time of day types</td>
</tr>
<tr>
<td align="left"><code>/api/forecasts/place-types</code></td>
<td align="left">returns a list of place types</td>
</tr>
<tr>
<td align="left"><code>/api/forecasts/wind-types</code></td>
<td align="left">returns a list of wind types</td>
</tr>
</tbody>
</table>
