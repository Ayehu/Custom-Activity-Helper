#     Ayehu.Sdk.ActivityCreation v1.0.9

This dll should replace older versions under every Ayehu NG Executor folder. 

This version includes the following:

1. Auto convert to Ayehu NG resultset:

	A. GenerateActivityResult(string)

	B. GenerateActivityResult(datatable)

	C. GenerateActivityResult(json string)

2. AyehuHelper class supporting the following functions:

     A. queryStringBuilder - support single and array key/value.

string queryStringBuilder(Dictionary<string, string> queryStringArray)

	B. omitJsonEmptyorNull - clear empty/null values in payload.

string omitJsonEmptyorNull(string theJson)

	C. JWT token generator.

string JWTToken(string APIKey, string Secret, string Algorithm, string Type, int Expseconds)

	D. URL content encoder

static HttpContent formUrlEncodedContent(string input)


