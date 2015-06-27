# pat-body-tweets

Textpattern CMS plugin.

Add Twitter links into your text content kind of the comment system into the [Medium's website](http://medium.com) (optional). Allow visitors to Tweet parts of text content on mouse selection as shown on [The (New) Guardian](http://next.theguardian.com) website (optional). Note: These two tags are independents.

## Add an icon for Twitter in front of each text parts (generate an individual anchor into each Tweets)
**All followed tags are intended to be used as single ones, not container ones**.

**Usage (all browsers capable)**:

    <txp:pat_body_tweets tag="" full="" sign="" tooltip="" class="" content="" />

## Attributes

> *tag* string (optional): choose which HTML tag surronding your text content on where to apply the anchors. Default: p. Note: only p, li, h(1-6) tags are allowed.
>
> *full* boolean (optional): Sets on 1, the Tweet will ne cut then followed by hyphens un ordre to respect the 140 caractères limit by Twitter. Default: 1 (true).
>
> *sign* string (optional): the sign to used un front of each anchors. Default: +.
>
> *tooltip* string (optional): the tooltip for each anchors. Default: empty (none).
>
> *class* string (optional): the class selector for each anchors. Default: "notes-maker".
>
> *content* string (optional): choose among "body" or "excerpt" your text on which to apply the anchors. Default: body.


## Allow your visitors to Tweet parts of your text content on mouse selection (do not generate any anchors, just article URL into the Tweets)

**Usage (IE9+ & all modern browsers capable)**

Place this code into your page template just before the last <code>&lt;/body&gt;</code> HTML tag:

    <txp:pat_body_tweets_live id="" account="" label="" popup="" info="" tooltip="" position="" top="" right="" bottom="" color="" style="" />

## Attributes

> *id* string (optional): the selector id of your HTML content where to limit the live Twitter selection. Default: "wrapper".
>
> *account* string (required): your Twitter account (i.e. @txpfr). Default: empty (none).
>
> *label* string (optional): the alternative text for the Twitter button. Default: Tweet it!.
>
> *popup* boolean (optional): chose to open the Twitter page into a popup. Default: 0 (open a new browser tab).
>
> *info* boolean (optional): choose to display a Twitter icon just after the HTML content designed by the *id* attribute. Default: 0 (no icon shown).
>
> *tooltip* string (optional): the tooltip for the Twitter icon if used. Default: "You can Tweet this text on mouse sélection".
>
> *position* boolean (optional): choose where to place the Twitter icon on the top or on the bottom of your text content identified with the "id" attribute. Default: 0 (top).
>
> *top* integer (optional): the CSS value position for the Twitter icon. Default: empty (none).
>
> *right* integer (optional): same as above for the right position. Default: empty (none).
>
> *bottom* integer (optional): same as above for the bottom position. Default: empty (none).
>
> *colors* string (optional): the background color for the Twitter button. Default: official Twitter color.
>
> *style* string (optional): any CSS rules to inject for your convenience. Default: empty (none).



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/cara-tm/pat-body-tweets/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

