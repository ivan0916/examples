Three examples of android code from my work at Jobinhood. I believe this code is outdated/incomplete as I was only able to get a local copy from an old machine. I no longer have access to the Jobinhood repo.

## ConversationList.java

This is part of a messaging module, the primary function of this class is to build a conversation from a JSON response retrieved by the home server. 

Contains examples of:
- JSON parsing
- ArrayList, SparseArray
- Date, date formatting

## SantiagoAndroid.java

This module handles requests to the home server for information (such as user details) or new messages from the server.

Contains examples of
- Static methods
- HTTP Response, Requests
- Threading
- JSON parsing

## ConversationListFragment.java

This module showcases some examples of android functionality. Also functions to dynamically generate content for a view (Loading conversations into a list view based on array entities).

Contains examples of:
- ListFragment
- Intents
- View, TextView, ListView, ImageView
