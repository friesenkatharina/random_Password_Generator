#random Password Generator
using html css javascript
responsive for mobile devices/mobile first

             ************************************************************
                      modernere Clipboard API Methode,
           speziell die navigator.clipboard.writeText() Methode.

> German<

<!-- Document.execCommand("copy") war früher eine verbreitete Methode, um Inhalte in die Zwischenablage zu kopieren, ist aber mittlerweile als veraltet markiert und sollte nicht mehr verwendet werden -->

Wichtige Punkte:

    Elementauswahl: Stellen Sie sicher, dass passwordBox auf ein <input> oder <textarea> Element verweist, da select() nur für diese Elementtypen funktioniert.

    Clipboard API: Die navigator.clipboard.writeText() Methode ist eine moderne und versprechensbasierte Methode, um Text in die Zwischenablage zu kopieren. Dies funktioniert jedoch nur, wenn die Webseite HTTPS verwendet oder die Seite lokal über localhost bedient wird.

    Fehlerbehandlung: Die Methode writeText() gibt ein Promise zurück, daher ist es sinnvoll, .then() und .catch() für Erfolgs- und Fehlerbehandlung zu verwenden.

    Berechtigungen: Beachten Sie, dass Benutzer eventuell ihre Berechtigungen anpassen müssen, um das Kopieren in die Zwischenablage zu erlauben, insbesondere bei der Verwendung in einigen Browsern oder Umgebungen.

> Englisch<
> Modern Clipboard API method, specifically the `navigator.clipboard.writeText()` method.

<!-- The `document.execCommand("copy")` method was previously a common way to copy content to the clipboard, but it is now marked as obsolete and should no longer be used -->

Important Points:

- **Element Selection**: Ensure that `passwordBox` refers to an `<input>` or `<textarea>` element, as `select()` only works for these types of elements.

- **Clipboard API**: The `navigator.clipboard.writeText()` method is a modern and promise-based method for copying text to the clipboard. However, this only works if the website uses HTTPS or if the page is served locally via `localhost`.

- **Error Handling**: The `writeText()` method returns a promise, so it makes sense to use `.then()` and `.catch()` for success and error handling.

- **Permissions**: Note that users may need to adjust their permissions to allow copying to the clipboard, especially when used in some browsers or environments.
