T4MVC is a T4 template for ASP.NET MVC apps that creates strongly typed helpers that eliminate the use of literal strings in many places.

e.g. instead of

````c#
@Html.ActionLink("Delete Dinner", "Delete", "Dinners", new { id = Model.DinnerID }, null)
````

T4MVC lets you write

````c#
@Html.ActionLink("Delete Dinner", MVC.Dinners.Delete(Model.DinnerID))
````

and that's just the beginning!

### Use the following links to get started

*   **Install** T4MVC in your MVC app using [NuGet](http://nuget.org)
*   **Watch**: watch an 8 minute [intro video on Channel 9](http://channel9.msdn.com/posts/jongalloway/Jon-Takes-Five-with-David-Ebbo-on-T4MVC/)
*   **Learn**: visit the [Documentation page](https://t4mvc.codeplex.com/documentation)
*   **Install** a VS Extension to automatically rerun T4MVC on build. You can use [AutoT4MVC](http://visualstudiogallery.msdn.microsoft.com/8d820b76-9fc4-429f-a95f-e68ed7d3111a) or [Chirpy](http://chirpy.codeplex.com/).
*   **Discuss**: Discuss it on [https://t4mvc.codeplex.com/discussions](https://t4mvc.codeplex.com/discussions)
*   **Contribute**: learn how on the [Contributor page](/wikipage?title=T4MVC_contrib&amp;referringTitle=Home "T4MVC_contrib&amp;referringTitle=Home")
*   **News**: [Follow David Ebbo on Twitter](http://twitter.com/davidebbo/) to get T4MVC announcements.
*   **History &amp; release notes**: [change history](/wikipage?title=T4MVC_History&amp;referringTitle=Home "T4MVC_History&amp;referringTitle=Home")
*   **Known issues**: find the list of known issues [here](/wikipage?title=T4MVC_KnownIssues&amp;referringTitle=Home "T4MVC_KnownIssues&amp;referringTitle=Home")
*   **Twitter quotes**: cool things people are saying on Twitter [here](/wikipage?title=T4MVC_Twitter&amp;referringTitle=Home "T4MVC_Twitter&amp;referringTitle=Home")

T4MVC is part of the [MvcContrib](http://mvccontrib.codeplex.com) project, which is part of the [Outercurve Foundation](http://www.outercurve.org/)
