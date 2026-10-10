# Get Pokémon Details

Retrieves detailed information about a specific Pokémon, including its abilities and name.

---

## Request

### HTTP Request
`GET https://pokeapi.co/api/v2/pokemon/{name_or_id}`

### Path Parameters

| Parameter | Type | Required | Description |
| :--- | :--- | :--- | :--- |
| `name_or_id` | `string` / `integer` | **Yes** | The name (e.g., `ditto`) or ID of the Pokémon. |

---

## Response

### Example Response Body (`200 OK`)

```json
{
  "id": 132,
  "name": "ditto",
  "base_experience": 101,
  "weight": 40
}