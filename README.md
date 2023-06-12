# BlazorThemeIdentity
Use Blazor Theme with Identity

The identity pages use the layout in the file \Pages\Shared_Layout.cshtml.

So you need to make _Layout.cshtml file behave the same as the \Shared_Host.cshtml and \Shared\MaintLayout.razor working together.

One difficulty is cshtml do not seem to load the Blazor-generated css files, so I had to manully add the generated styles to the \wwwroot\css\site.css. If you are not using Blazor-generated css files, then you do not need to update the site.css file.

Note the custom css at the bottom of the site.css file:
