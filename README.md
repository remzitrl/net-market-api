<div class="Box-sc-g0xbh4-0 js-snippet-clipboard-copy-unpositioned DirectoryRichtextContent-module__SharedMarkdownContent--YORdJ" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">Supermarket API</h1><a id="user-content-supermarket-api" class="anchor" aria-label="Permalink: Supermarket API" href="#supermarket-api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><a href="#contributors-"><img src="https://camo.githubusercontent.com/220c6437a6d43c1e326bd0e0e97a44ba087517c52589edec5df662068ee2a519/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f616c6c5f636f6e7472696275746f72732d31312d6f72616e67652e7376673f7374796c653d666c61742d737175617265" alt="All Contributors" data-canonical-src="https://img.shields.io/badge/all_contributors-11-orange.svg?style=flat-square" style="max-width: 100%;"></a></p>

<p dir="auto">Simple RESTful API built with ASP.NET Core and .NET 8 to show how to create RESTful services using a decoupled, maintainable architecture.</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Changes list</h2><a id="user-content-changes-list" class="anchor" aria-label="Permalink: Changes list" href="#changes-list"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Many changes were made to the code presented at the tutorial published on <a href="https://medium.com/free-code-camp/an-awesome-guide-on-how-to-build-restful-apis-with-asp-net-core-87b818123e28" rel="nofollow">Medium</a> and <a href="https://www.freecodecamp.org/news/an-awesome-guide-on-how-to-build-restful-apis-with-asp-net-core-87b818123e28/" rel="nofollow">freeCodeCamp</a>, to make the API code cleaner and to add functionalities that developers may find useful.</p>
<p dir="auto">If you want to download the original code showed on the tutorial, download the <a href="https://github.com/evgomes/supermarket-api/releases/tag/1.0.0">1.0.0</a> tag.</p>
<ul dir="auto">
<li>
<p dir="auto">2.1.0 <em>[February 9, 2024]</em></p>
<ul dir="auto">
<li>Updated .NET version to .NET 8.</li>
<li>Updated libraries to match the most recent .NET version.</li>
<li>Added Docker support.</li>
<li>Refactored code to use expression body methods, primary constructors, and new object and collection initialization.</li>
<li>Added <code>required</code> constraint to resources.</li>
</ul>
</li>
<li>
<p dir="auto">2.0.0 <em>[July 5, 2023]</em></p>
<ul dir="auto">
<li>Updated .NET version to .NET 7.</li>
<li>Updated AutoMapper, Entity Framework Core, and Swashbuckle dependencies to match .NET 7.</li>
<li>Enabled implicit usings and nullable types.</li>
<li>Added global usings and removed implicit namespaces from the source code.</li>
<li>Renamed the <code>UnitOfMeasurement</code> enum type to make it follow the official naming convention.</li>
<li>Removed <code>CategoryResponse</code> and <code>ProductReponse</code> types to use a generic <code>Response&lt;T&gt;</code> record type instead.</li>
<li>Changed API resources to use record types instead of classes, and to initialize values in an immutable way using <code>init</code>.</li>
<li>Added configuration to make all API routes lower-case.</li>
<li>Refactored services to include logging using the standar .NET logging provider and to make code cleaner.</li>
</ul>
</li>
<li>
<p dir="auto">1.4.0 <em>[November 26, 2021]</em></p>
<ul dir="auto">
<li>Updated .NET version to .NET 5 (see <a href="https://github.com/evgomes/supermarket-api/pull/11" data-hovercard-type="pull_request" data-hovercard-url="/evgomes/supermarket-api/pull/11/hovercard">#11</a>)</li>
<li>Updated AutoMapper, Entity Framework Core, and Swashbuckle dependencies to match .NET 5.</li>
<li>Created <code>BaseApiController</code> class to standardize routes and to automatically apply data annotations validation by using the <code>ApiController</code> attribute.</li>
<li>Refactored logic to seed database data and to apply entity type configuration for application models.</li>
</ul>
</li>
<li>
<p dir="auto">1.3.0 <em>[December 15, 2019]</em></p>
<ul dir="auto">
<li>Updated ASP.NET Core version to 3.1, fixed issues related to InMemoryProvider, updated Swagger (see <a href="https://github.com/evgomes/supermarket-api/pull/5" data-hovercard-type="pull_request" data-hovercard-url="/evgomes/supermarket-api/pull/5/hovercard">#5</a>).</li>
<li>Fixed paging calculation mistake, updated descriptions, updated "launchSettings.json" to open Swagger on running the application.</li>
</ul>
</li>
<li>
<p dir="auto">1.2.1 <em>[August 11, 2019]</em></p>
<ul dir="auto">
<li>Changed <code>BaseResponse</code> to use generics as a way to simplify responses (see <a href="https://github.com/evgomes/supermarket-api/pull/3" data-hovercard-type="pull_request" data-hovercard-url="/evgomes/supermarket-api/pull/3/hovercard">#3</a>).</li>
</ul>
</li>
<li>
<p dir="auto">1.2.0 <em>[July 15, 2019]</em></p>
<ul dir="auto">
<li>Changed <code>/api/products</code> endpoint to allow pagination (see <a href="https://github.com/evgomes/supermarket-api/issues/1" data-hovercard-type="issue" data-hovercard-url="/evgomes/supermarket-api/issues/1/hovercard">#1</a>).</li>
</ul>
</li>
<li>
<p dir="auto">1.1.0 <em>[June 18, 2019]</em></p>
<ul dir="auto">
<li>Added Swagger documentation through <a href="https://github.com/domaindrivendev/Swashbuckle">Swashbuckle</a>.</li>
<li>Added cache through native <a href="https://docs.microsoft.com/en-us/aspnet/core/performance/caching/memory?view=aspnetcore-2.2" rel="nofollow">IMemoryCache</a>.</li>
<li>Changed products listing to allow filtering by category ID, to show how to perform specific queries with EF Core.</li>
<li>Changed ModelState validation to use <em>ApiController</em> attribute and <em>InvalidResponseFactory</em> in <em>Startup</em>.</li>
</ul>
</li>
<li>
<p dir="auto">1.0.0 <em>[February 4, 2019]</em></p>
<ul dir="auto">
<li>First version of the example API, presented in the tutorial on <a href="https://medium.com/free-code-camp/an-awesome-guide-on-how-to-build-restful-apis-with-asp-net-core-87b818123e28" rel="nofollow">Medium</a> and <a href="https://www.freecodecamp.org/news/an-awesome-guide-on-how-to-build-restful-apis-with-asp-net-core-87b818123e28/" rel="nofollow">freeCodeCamp</a>.</li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Frameworks and Libraries</h2><a id="user-content-frameworks-and-libraries" class="anchor" aria-label="Permalink: Frameworks and Libraries" href="#frameworks-and-libraries"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-7.0" rel="nofollow">ASP.NET Core 7</a>.</li>
<li><a href="https://docs.microsoft.com/en-us/ef/core/" rel="nofollow">Entity Framework Core</a> (for data access).</li>
<li><a href="https://docs.microsoft.com/en-us/ef/core/miscellaneous/testing/in-memory" rel="nofollow">Entity Framework In-Memory Provider</a> (for testing purposes).</li>
<li><a href="https://automapper.org/" rel="nofollow">AutoMapper</a> (for mapping resources and models).</li>
<li><a href="https://github.com/domaindrivendev/Swashbuckle">Swashbuckle</a> (API documentation).</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">How to Test</h2><a id="user-content-how-to-test" class="anchor" aria-label="Permalink: How to Test" href="#how-to-test"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">First, download and install the <a href="https://dotnet.microsoft.com/en-us/download" rel="nofollow">.NET Core SDK</a>.</p>
<p dir="auto">If you have Docker and Visual Studio installed on your machine, you can open the solution file using Visual Studio and run the project using the Docker profile.</p>
<p dir="auto">If not, open the terminal or command prompt at the API root path (<code>/src/Supermarket.API/</code>) and run the following commands, in sequence:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>dotnet restore
dotnet run
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="dotnet restore
dotnet run" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">Navigate to <code>http://localhost:5000/api/categories</code> to check if the API is working. If you see a HTTPS security error, just add an exception to see the results.</p>
<p dir="auto">Navigate to <code>http://localhost:5000/swagger</code> to check the API documentation and to test all API endpoints.</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/evgomes/supermarket-api/master/images/swagger.png"><img src="https://raw.githubusercontent.com/evgomes/supermarket-api/master/images/swagger.png" alt="API Documentation" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Contributors ✨</h2><a id="user-content-contributors-" class="anchor" aria-label="Permalink: Contributors ✨" href="#contributors-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Thanks goes to these wonderful people (<a href="https://allcontributors.org/docs/en/emoji-key" rel="nofollow">emoji key</a>):</p>



<markdown-accessiblity-table data-catalyst=""><table>
  <tbody><tr>
    <td align="center"><a href="https://github.com/mattbarry"><img src="https://avatars.githubusercontent.com/u/1567119?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>Matt Barry</b></sub></a><br><a href="https://github.com/evgomes/supermarket-api/commits?author=mattbarry" title="Code">💻</a></td>
    <td align="center"><a href="https://hippiezhou.fun" rel="nofollow"><img src="https://avatars.githubusercontent.com/u/13598361?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>hippie</b></sub></a><br><a href="https://github.com/evgomes/supermarket-api/commits?author=hippieZhou" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/NoobInTraining"><img src="https://avatars.githubusercontent.com/u/23185961?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>NoobInTraining</b></sub></a><br><a href="https://github.com/evgomes/supermarket-api/commits?author=NoobInTraining" title="Code">💻</a></td>
    <td align="center"><a href="https://www.linkedin.com/in/mahmmoud-kinawy-7928b218a/" rel="nofollow"><img src="https://avatars.githubusercontent.com/u/57391128?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>Ma'hmmoud Kinawy</b></sub></a><br><a href="https://github.com/evgomes/supermarket-api/commits?author=mahmmoudkinawy" title="Code">💻</a></td>
    <td align="center"><a href="https://www.linkedin.com/in/arazauk/" rel="nofollow"><img src="https://avatars.githubusercontent.com/u/22678337?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>Ahsan Raza</b></sub></a><br><a href="https://github.com/evgomes/supermarket-api/pulls?q=is%3Apr+reviewed-by%3AAhsanRazaUK" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/dundich"><img src="https://avatars.githubusercontent.com/u/1078713?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>dundich</b></sub></a><br><a href="#ideas-dundich" title="Ideas, Planning, &amp; Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/thedon-chris"><img src="https://avatars.githubusercontent.com/u/30728737?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>thedon_chris</b></sub></a><br><a href="https://github.com/evgomes/supermarket-api/issues?q=author%3Athedon-chris" title="Bug reports">🐛</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/subhanisyed17"><img src="https://avatars.githubusercontent.com/u/46715997?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>subhanisyed17</b></sub></a><br><a href="https://github.com/evgomes/supermarket-api/issues?q=author%3Asubhanisyed17" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://www.geekcafe.com" rel="nofollow"><img src="https://avatars.githubusercontent.com/u/3632968?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>Eric Wilson</b></sub></a><br><a href="#question-eric-wilson" title="Answering Questions">💬</a></td>
    <td align="center"><a href="https://github.com/Pham-Tuan-Phat"><img src="https://avatars.githubusercontent.com/u/61822642?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>Phạm Tuấn Phát</b></sub></a><br><a href="#ideas-Pham-Tuan-Phat" title="Ideas, Planning, &amp; Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/miki-nis"><img src="https://avatars.githubusercontent.com/u/12809735?v=4?s=100" width="100px;" alt="" style="max-width: 100%;"><br><sub><b>miki-nis</b></sub></a><br><a href="https://github.com/evgomes/supermarket-api/issues?q=author%3Amiki-nis" title="Bug reports">🐛</a></td>
  </tr>
</tbody></table></markdown-accessiblity-table>



<p dir="auto">This project follows the <a href="https://github.com/all-contributors/all-contributors">all-contributors</a> specification. Contributions of any kind welcome!</p>
</article></div>
