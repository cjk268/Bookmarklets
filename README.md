# Bookmarklets  

## 1. Remove Sidebar from Old Reddit  

### Bookmarklet Code  
```javascript
javascript:(function(){document.querySelector(".side").remove();})();
```

The sidebar on old Reddit can be annoying, especially when resizing the window. Add this bookmarklet to your bookmarks bar and click it to remove the sidebar.  

Alternatively, you can add an ad block filter, but the sidebar is often useful and this lets you toggle when not needed.  

### Before → After  
<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/86acd6d9-80b1-4872-9185-57d1a8f48b57" width="300"></td>
    <td><strong>→</strong></td>
    <td><img src="https://github.com/user-attachments/assets/1366d1cc-93fe-4434-a413-aab7cbfac648" width="300"></td>
  </tr>
</table>

## 2. Subreddit Top of the Week
### Bookmarklet Code  
```javascript
javascript:(function(){window.location.href=`${window.location.href}top/?sort=top&t=week`;})();
```
This bookmarklet takes you to the top posts of the week for the subreddit you're currently viewing. Of course, you can adjust the time range by changing the `t` query parameter to `hour`, `day`, `month`, `year`, or `all`.
