snipmatch-snippets
========================

Forked from the official [org.eclipse.recommenders.snipmatch.snippets repository](http://git.eclipse.org/c/recommenders/org.eclipse.recommenders.snipmatch.snippets.git/) to work on some [Eclipse Scout](http://www.eclipse.org/scout) specific snippets.

With version `2.1.11.v20141112-1056` of Snipmatch (Mars M3), it is possible to work with multiple Snippet repositories. 
On branch `format-5` (the corresponding branch) the snippets already defined in *Eclipse Code Recommenders Snippet Repository* have been deleted from this repository. Otherwise they were defined twice.


Documentation on https://www.eclipse.org/recommenders/manual/#snipmatch

The snippets(git repository) are located in MY_WORKSPACE/.recommenders/snipmatch/repositories/MY_REPOSITORY_URL. The repository URL has all special characters (like slashes, colons, or dashes) replaced by underscores. Each snippet is stored in its own file that has the snippet’s UUID as its name.
