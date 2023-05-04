# zotero-things
Something related to Zotero.
This is the place I upload or writing code for personal use in case of Zotero, a citation manager.
These file may be collected elsewhere on the Internet, and I have made some modifications for personal usage.
Please feel free to use them, if you like!

# engine.json
I have add these code to to search an article in Researchgate.

	{
		"_name": "Researchgate",
		"_alias": "Researchgate",
		"_description": "Researchgate Search",
		"_icon": "https://www.researchgate.net/favicon.ico",
		"_hidden": false,
		"_urlTemplate": "https://www.researchgate.net/search.Search.html?query={z:DOI}&type=publication",
		"_urlParams": [],
		"_urlNamespaces": {
			"z": "http://www.zotero.org/namespaces/openSearch#",
			"": "http://a9.com/-/spec/opensearch/1.1/"
		},
		"_iconSourceURI": "http://www.researchgate.net/favicon.ico"
	},
	
