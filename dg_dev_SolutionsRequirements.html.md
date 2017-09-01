# Solutions

YaaS is a platform to build any kind of solution, not just APIs or tools. Single cloud solutions are based on one or more YaaS Market packages. They require proper architectural documentation so your subscribers understand which packages implement each piece of functionality. The Solutions documentation also includes details about extensibility, customization, and what functionality the subscriber can unplug and replace with the subscriber's own solutions. The Dev Portal has a dedicated space for Solutions documentation.

Follow the <a href="#AbouttheStyleandStandards">Styles and Standards</a> for many agreed-upon standards, including word choices, use of acronyms, and the SAP Hybris product names.

## Required documents
Write each major section of the Solutions documentation in a separate file. Use the proper metadata as described in the <a href="/tools/documentationsdk/#Metadata"> Metadata</a> section of the Documentation SDK and add content source files to your repository with the following directory structure:
<strong>
- docu
 - solutions
   - {{topicName}}
</strong>
<div class="panel note"> Use lowercase only and no spaces for the <strong>topicName</strong>. For example, `hybrisprofile`.
</div>

Solutions are unique by nature. This is why each solution requires a separate set of documents. Remember that your reader wants to know:
- How the whole solution works
- What packages it is based on and how they interact
- How to replace a certain package with a custom solution
- How to extend and customize

Your new documentation for a solution can include the following sections. 

### Overview
In the first document, add a short introduction that explains the nature of your solution and what business value it brings to the reader. Add a list of features that the solution implements.

### Package list
Add a section that informs the user about the packages and services your solution includes, such as this example shows:

<table class="table table-striped table-glossary techne-table">
<tr><th>Packages</th><th>Services</th></tr>
<tr><td>First Package</td><td>[Service A](https://example1.com)</td></tr>
<tr><td>Second Package</td><td>[Service A](https://example1.com) <br> [Service B](https://example2.com)</td></tr>
</table>

### Details
This section describes the details of your solution in a logical order. For example, provide a Getting Started Guide, any integration instructions, and add a Troubleshooting section.

## Structure documents in the navigation
Group documents of the same **type** and create the left-hand navigation as described in the <a href="/tools/documentationsdk"> Documentation SDK</a>.

### Example
For an example of unique solution documentation, see the <a href="/solutions/saphybrisprofile/index.html">SAP Hybris Profile</a> documentation.
