# Simplest if statement
Displays the contents of the statement if the asset has a value in a metadata field called "foo".
```
%begin_asset_metadata_foo%
Bar
%end_asset_metadata_foo%
```
# Simplest if else statement
Displays different messages depending on whether the user is logged in.
```
%begin_user_logged_in%
You are logged in
%else_user_logged_in%
You are not logged in
%end_user_logged_in%
```

# If statement with condition
Displays "Hi Steve" if the asset's name is "Steve".
```
%begin_asset_attribute_name^eq:Steve%
Hi Steve
%begin_asset_attribute_name^eq:Steve%
```
