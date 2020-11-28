# Jasonette Snippets

The snippets in this repo were ported to Sublime Text from [Jasonette snippets](https://github.com/felipemullen/jasonette-snippets) made for Visual Studio Code.

## List of Snippets

| Prefix | Jasonette Snippet Content |
| ------ | ------------ |
| `$jason` | `A new jasonette app base` |
| `href` | `Used to describe links between views` |
| `$require` | `The $require action imports remote JSON files in parallel` |
| `$lambda` | `Call another action by name` |
| `$reload` | `Refreshes the view completely by re-fetching content from the current URL` |
| `$render` | `Renders a template with data` |
| `$snapshot` | `Takes a snapshot of the currently visible screen` |
| `$href` | `An action version of href. Works the same way, but can be used when a component doesn't support href attribute directly` |
| `$close` | `Close a modal (works when the currently view is a modal)` |
| `$back` | `Transition one step back from the current view. If the current view is a modal, it closes the current view, otherwise it slides back to the previous view` |
| `$network.request` | `Make GET/POST/PUT/DELETE Action requests` |
| `$network.upload` | `Upload data to cloud providers. Currently supports S3` |
| `$session.set` | `$session.set takes care of token authentication to authenticate into any mobile API` |
| `$session.reset` | `This action lets you clear sessions for a specified domain. Can be used for both token authentication and web authentication via cookies` |
| `$set` | `Use $set and $get to set and get local variables.` |
| `$get` | `Use $set and $get to set and get local variables.` |
| `$cache.set` | `$cache.set action is used to store to cache` |
| `$cache.get` | `Directly access $cache variable from a template expression` |
| `$cache.reset` | `Use $cache.reset action to reset the cache associated with the current url` |
| `$global.set` | `$global.set action is used to write to global variables` |
| `$global.get` | `Read global variables using template expressions` |
| `$global.reset` | `Use $global.reset action to remove global variables by name` |
| `$util.banner` | `Displays a banner notification with title and description` |
| `$util.toast` | `Displays a toast notification with a simple text` |
| `$util.alert` | `Displays an alert` |
| `$util.share` | `Share a text, image, video, or a combination of them` |
| `$util.picker` | `Opens a multiple choice picker menu, with each item linking to an action or an href` |
| `$util.datepicker` | `Opens a datepicker and returns the value in unix time format` |
| `$util.addressbook` | `Fetches the addressbook to populate them into $jason` |
| `$media.camera` | `Capture a video or a photo using the device camera` |
| `$media.picker` | `Opens the device camera roll` |
| `$media.play` | `plays a video from remote url` |
| `$audio.play` | `Play audio from remote url` |
| `$audio.pause` | `Pauses an audio clip that's already playing from a remote url` |
| `$audio.stop` | `Stops an audio clip that's already playing from a remote url. If URL is specified, stops ONLY this url. Otherwise, stops all audios currently playing` |
| `$audio.seek` | `Seeks audio already playing from a remote url` |
| `$audio.position` | `Get the position of the specified audio clip` |
| `$audio.duration` | `Returns total duration of the specified audio clip in seconds` |
| `$audio.record` | `Records audio` |
| `$geo.get` | `Get user's geolocation using accuracy in meters` |
| `$timer.start` | `Start a timer using seconds as a countdown` |
| `$timer.stop` | `Stops a timer using the name of the timer` |
| `$convert.csv` | `Converts CSV to parsed JSON` |
| `$convert.rss` | `Convert RSS to JSON. Built on top of node-feedparser library` |
| `label` | `Static uneditable text element` |
| `image` | `Image loaded from either remote url or data-url` |
| `button` | `A basic component that responds to user tap` |
| `textfield` | `Single line input field` |
| `textarea` | `Multiline input field` |
| `slider` | `Horizontal slider input` |
| `html` | `A self-contained web environment that you can plug in, style, and manipulate just like the rest of the components` |
| `space` | `An empty space component mostly used for layout purposes` |
| `map` | `Map component` |
| `layout` | `A layout to store components in` |
| `nestedlayout` | `A layout to store components in` |
| `each` | `Iterates through the expression that comes after declaration` |
| `if` | `Single conditional statement` |
| `ifelse` | `Conditional statement including else` |
| `elseif` | `Conditional statement including else` |
| `this` | `This keyword` |
| `mixin` | `Mixin Helper` |

## Author

<table>
  <thead>
    <tr>
      <th valign="middle" align="center">
        <a href="https://barrymode.com"><img alt="BarryMode" src="https://avatars3.githubusercontent.com/u/5648875?v=2&s=160" width="80" height="80"></a>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="middle" align="center">
        <a href="https://barrymode.com"><strong>BarryMode</strong></a><br>
        <a href="https://www.youtube.com/barrymode"><img src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/youtube.svg" width="16" height="16"></a> <a href="https://github.com/barrymode"><img src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/github.svg" width="16" height="16"></a><br>
        <a href="https://www.paypal.me/BarryMode"><img src="https://img.shields.io/badge/Give%20Coffee--00653b.svg?style=social&labelColor=fff&logo=data:image/png;base64,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"></a>
      </td>
    </tr>
  </tbody>
</table>

