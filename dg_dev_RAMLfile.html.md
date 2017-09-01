# RAML file

YaaS services use the RESTful API Modeling Language (RAML) to describe their own APIs in a natural and intuitive way. Follow the <a href="/tools/apiguidelines">API Guidelines</a>. and create consistent and straightforward RAML API definitions.<br/>

The Dev Portal uses the RAML file as the source for the automatic generation of the <strong>API Reference</strong> section in the API Docs. For a coherent user experience, include up-to-date examples and clear descriptions. Make the explanations concise and move the more extensive content to the **Details** or **Tutorial** section. Remember that the YaaS <a href="#AbouttheStyleandStandards">Style and Standards</a> guidelines apply when you document your endpoints and methods in the RAML file:
<ul>
    <li>Focus on the user's task and avoid unnecessary words.</li>
    <li>Use second person, active voice, and present tense.</li>
    <li>Stick to the preferred terminology and format standards.</li>
    <li>Use appropriate articles and punctuation.</li>
</ul>
For example: </br>"Use the <code>/all</code> endpoint to return a list of all tenants for a given client."

<div class="panel note">Because the content of the RAML file appears as part of the API Documentation, a review is required for the RAML file descriptions, or any content that displays publicly.
</div>
