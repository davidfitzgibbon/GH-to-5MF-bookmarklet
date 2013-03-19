GH-to-5MF-bookmarklet
=====================

Easy bookmarklet to view a repo in 5minutefork.com

All you need to do is [drag this bookmarklet to your bookmarks bar](javascript:(function(){(function(){var url = window.location.href;url = url.replace(/^https:\/\//i, 'http://');url = url.replace('github.com', '5minutefork.com');location = url;})();})();)

Want to try it out? Just click the link!
