# Mini Challenge 3

## Draft and Archive support

### Acceptance Criteria
1. There should be a list of "draft" posts (these are only visible to the logged in user and nobody else).
2. There should be a list of "archived" posts (these should only be accessible/visible to logged in users).

### Bonus
The DetailView should be consistent with the rules specified above.


Password Change Template Names:
template_name = "registration/password_change_form.html"

Password Change Done Template Names:
template_name = "registration/password_change_done.html"

Tip for easy secret keys:
python3 -c "import secrets; print(secrets.token_urlsafe())"


If you lose blog link, in Ubuntu:
heroku open