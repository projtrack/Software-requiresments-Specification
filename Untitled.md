Issue_id: int
Issue_author: object
	Account {
		Account_id
		Account_Username
	}
Body:
	Content {
	Type: String
	Content {
		type: String
		text: String
	}
	}
	Author: Object {
		Update_user: object
		{
			Account_id : Int
			Account_name : String
			active : Boolean
		}
	}
	Created : Datetime
	Updated: Datetime
visibility": {
"type": "role",
"value": "Administrators"
}