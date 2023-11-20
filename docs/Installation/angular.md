# Angular Installation

--> Angular modules will run on NODE JS, so first we need to install NODE JS software.

Please use below link to get latest NODE JS software.

<pre><code class="shell">https://nodejs.org/en/download</code></pre>

Install node version min v18 or above.

Once we install NODE, please check version information using CMD prompt.

<pre><code class="shell">Win+R -> CMD</code></pre>
<pre><code class="shell"></code></pre>

Enter below command to display version number.

<pre><code class="shell">C:\Users\gadda>node --version</code></pre>

<pre><code class="shell">v20.9.0</code></pre>

We need NPM to load modules or install, NPM will be installed by deafult along with NODE. Please check the NPM version after installation of NODE. Use below command to display the NPM version.

<pre><code class="shell">C:\Users\gadda>npm --version</code></pre>

<pre><code class="shell">10.1.0</code></pre>

Once we install node we need to install angular cli by using NPM, for more details about angular setup please refer below URL.

<pre><code class="shell">https://angular.io/cli</code></pre>

angular modules -> angular/cli -> npm -> node js

Run below command in CMD prompt to install angular CLI.

<pre><code class="shell">npm install -g @angular/cli</code></pre>

The above command will install major version of angulat CLI, if we need latest stable version as of today 19th NOV 2023. Please use below command.

<pre><code class="shell">npm install -g npm@10.2.4</code></pre>

Once we installed angular CLI, please run the below command to check the version.

<pre><code class="shell">ng version</code></pre>

If everything is good, we are okay to proceed further to create a new angular project by using below steps.

----How to create a new angular project----

Run below command in CMD prompt.

<pre><code class="shell">ng new helloworld</code></pre>

-- To execute/or build angular project, please follow below steps.

<pre><code class="shell">cd helloworld</code></pre>

<pre><code class="shell">ng serve</code></pre>

Code wil get published in localhost, if no errors/compilation issues.

Sample localhost url#

http://localhost:4200/
