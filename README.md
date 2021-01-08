# Top-Trumps
JQuery Top Trumps game

## Notes 
The $.fn is an alias for jQuery.prototype which allows you to extend jQuery with your own functions.


This is a list of all available callbacks. The params should be understandable without further explanation (except: $ marks variables as jQuery objects).

<table>
  <tr>
    <th>Function</th>
    <th>Params</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>onInit</td>
    <td>$instance, settings</td>
    <td>Will be called after top trumps has been built.</td>
  </tr>
  <tr>
    <td>onComplete</td>
    <td>$instance, settings</td>
    <td>Will be called when game ends.</td>
  </tr>
  <tr>
    <td>renderCard</td>
    <td>$card, card, fields</td>
    <td>Use this method to change the look of your cards. For example you could add a fancy looking image.</td>
  </tr>
</table>
