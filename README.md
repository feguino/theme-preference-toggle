# Building a theme switch component
A website may provide settings for controlling the color scheme instead of relying entirely on the system preference. This means that users may browse in a mode other than their system preferences. For example, a user's system is in a light theme, but the user prefers the website to display in the dark theme.

There are several web engineering considerations when building this feature. For example, the browser should be made aware of the preference as soon as possible to prevent page color flashes, and the control needs to first sync with the system then allow client-side stored exceptions.
