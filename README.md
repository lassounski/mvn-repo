Lassounski Maven Repository
===========================

This is a repository where I maintain my maven projects that can be used inside any maven application.

Usage
----------

Suppose you are willing to use the PubMedDataset-1.0-SNAPSHOT in your project.

In your project pom.xml:

* Add to the following code to ```<repositories>```:
<pre>
    &lt;repositories&gt;
    ...
        &lt;repository&gt;
            &lt;id&gt;lassounski-snapshots&lt;/id&gt;
            &lt;url&gt;https://github.com/lassounski/mvn-repo/raw/master/snapshots&lt;/url&gt;
        &lt;/repository&gt;
    ...
    &lt;/repositories&gt;
</pre>

* And add the name and version of the project you want to use in ```<dependecies>```:
<pre>
    &lt;dependencies&gt;
        ...
        &lt;dependency&gt;
            &lt;groupId&gt;com.uenf&lt;/groupId&gt;
            &lt;artifactId&gt;PubMedDataset&lt;/artifactId&gt;
            &lt;version&gt;1.0-SNAPSHOT&lt;/version&gt;
        &lt;/dependency&gt;
        ...
    &lt;/dependencies&gt;
</pre>
That`s it, the .jar will be automatically downladed to your project dependencies and will be ready to use.

