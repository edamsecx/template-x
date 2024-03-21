# template-x
embed template parser | for Zenn
as EJS

```ejs
<ul id={uuid}>
  {for content of contents}
    <li>
      {if content.type === "article"}
        Article: {content.title}
      {elif content.type === "announce"}
        Announce: {content.title}
      {endif}
    </li>
{endfor}
</ul>
