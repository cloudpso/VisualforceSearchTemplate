Visualforce page with a first and/or last name search across Contacts.  Autocomplete passes a JSON string of Contact names, while the page controller extends a virtual class for reusable search methods.

https://raw.githubusercontent.com/mattparkerls/VisualforceSearchTemplate/master/complete.png

Entire controller is only several lines

```java
public class DeveloperController extends SearchUtils{

	public DeveloperController(){}

}
```

Error handling for user input less than 1 character or non-alpha characters.

![Screen Shot]
(https://raw.githubusercontent.com/mattparkerls/VisualforceSearchTemplate/master/error.png)
