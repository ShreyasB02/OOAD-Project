# Define classes for entities, and methods:
## figure out firebase for storage of songs with schema with global song repo(preuploaded) with genre, 
* user's songs(if artist),
 * user's playlist,
* "Add" button which "syncs" with songqueue
- give songs with same genre in a list

## Songqueue ( same as above, but view loads it. Global repo with genre)
- Can take in more songs if added by user

- Artist: maybe a bool in user, if triggered, allows the functions like upload an object of type Song

- Song: define the genre and artist name as types


## FIREBASE:
- song: artist name(check if username exists before), genre (common, give dropdown?)
- user : name ; isartist; songqueue_number ; playlist( subset of songqueue) ; songs (only ifartist== TRUE) ; password
