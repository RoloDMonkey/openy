# Branch
Branch content type is used for adding Branches on the site.

### Fields
| Name  | Machine name | Required | Description |
| ------------- | ------------- | ------------- | ------------- |
| Title  | drupal's default  | Yes | Title of the branch item. |
| Neighborhood | field\_location_area  | No | A taxonomy reference field using the "Area" vocabulary. |
| Coming Soon | field\_location_state  | No | A checkbox field to determine branches in development. |
| Temporary URL | field\_location\_temp_url  | No | A link field to provide a temporary page URL (a blog post, or smth else) if the branch is coming soon. |
| **Contact** | Field group |||
| Address | field\_location_address | Yes | An address field that will provide the ability to add details about the locations. Details to be completed: <ul><li>Address</li><li>City</li><li>State</li><li>Zip Code</li></ul> |
| Latitude | field\_location_latitude | No | Input for providing the latitude information. |
| Longitude | field\_location_longitude | No | Input for providing the longitude information. |
| Phone | field\_location_phone | Yes | Input for providing the phone information. |
| Fax | field\_location_fax | No | Input for providing the fax information. |
| Email | field\_location_email | No | Input for providing the email information. |
| Directions | field\_location_directions | No | A link field for adding the directions link. |
| **Branch Hours** | Field group |||
| Branch Hours | field\_branch_hours | Field collection | Field Collection to indicate the branch hours. |
| Day of the week | field\_branch\_hours_day | No | Select list with following values: <ul><li>sunday\|Sunday</li><li>monday\|Monday</li><li>tuesday\|Tuesday</li><li>wednesday\|Wednesday</li><li>thursday\|Thursday</li><li>friday\|Friday</li><li>saturday\|Saturday</li></ul> |
| Start/End Time | field\_branch\_hours_time | No | Textfield with description "e.g. 9am - 5pm, closed." |
| **Header Area** | Field group |||
| Content | field\_header_content | No | A paragraph embed field that will allow us to add various flexible content modules, from the predefined list of paragraph types. |
| **Content Area** | Field group |||
| Content | field_content | No | A paragraph embed field that will allow us to add various flexible content modules, from the predefined list of paragraph types. |

### URL pattern

Content type is using following pattern:
`/locations/[node:title]`
