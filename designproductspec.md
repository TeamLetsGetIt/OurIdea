# LiveCrowd

Your [design product spec](https://hackmd.io/SR5ovxoOTQ6cCrvQ33qnGw?edit) (described in that link) will look like the following in your README:

## 1. User Stories (Required and Optional)

**Required Must-have Stories**
 * register themselves as new users
 * log-in as existing user
 * ability to have lists of favourite songs, or be able to use songs from other apps(spotify, soundcloud,youtube)
 * have party rooms for people to join(using a party code)
 * ability to localise party rooms for nearby listeners
 * ability to vote on upcoming songs
 

**Optional Nice-to-have Stories**
 * ability to have private rooms where only certain listeners are allowed 
 * have radio-like channels that you can join from anywhere in the world so concerts or seminars can be broadcasted
 * have a maps feature to invite others to your party
 * have user profile distinctions, like event hosts, regular users, etc..
 * ability to choose to play live version of the song
 * no commercial interruptions and will only show in text box.

## 2. Screen Archetypes

 * Login Screen
   * Users can login/signup
 * Creation
   * User can host their party and invite people
   * Users can set party to public or private
 * Search
     * User can search for users to invite
 * Stream (Party Rooom screen)
   * Add song to a playlist
   * Vote a song up or down in the queue
   * Vote to add a song to queue
   * Vote to remove a song from queue
 *  Creation (Join a party sceen)
     *  Allows a user to join a party using a code that the host provides 
 * Stream (Home Screen)
    * shows parties in the area
 * Stream (Playlist Screen)
    * Personal profile with lists of songs/playlists that one can readily add when user joins a party
## 3. Navigation

**Tab Navigation** (Tab to Screen)

 * home screen (shows ongoing public parties around you)
 * Party room host screen
 * Join a party screen
 * profile screen

**Flow Navigation** (Screen to Screen)

 * Login/Register screen
   * home screen
 * Creation screen
   * search screen
   * Party room screen to add songs
 * Search screen
    * takes you back to party room screen
 * Profile screen
     * Playlist screen 
 *  Join a party sceen
    *  Playlist screen
 * Inside Party Screen
    * home screen
