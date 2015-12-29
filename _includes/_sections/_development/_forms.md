### Forms

- Logical layout
    Tab order of the form follows a logical pattern.

- Associated label for all form controls (e.g. input, select etc.)
    `<label for="name">Name:</label><input id="name" type="text">`

- Make sure placeholder attributes are NOT being used in place of label tags.
    An exception to this rule would be smaller forms with one or two fields (eg. search or log in forms)

- Group related form elements with fieldset and describe the group with legend  

    Important for `<input type="radio">` and `<input type="checkbox">`  

<pre><code class="language-markup">&lt;fieldset&gt;
    &lt;legend&gt;Output format&lt;/legend&gt;
    &lt;div&gt;
        &lt;input type="radio" name="format" id="txt" value="txt" checked&gt;
        &lt;label for="txt"&gt;Text file&lt;/label&gt;
        &lt;/div&gt;
    &lt;div&gt;
        &lt;input type="radio" name="format" id="csv" value="csv"&gt;
        &lt;label for="csv"&gt;CSV file&lt;/label&gt;
    &lt;/div&gt;
&lt;/fieldset&gt;
</code></pre>
