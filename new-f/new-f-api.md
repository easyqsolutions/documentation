# API Details

## List of api used in components and its description

> In code section the service name and function name is added Ex : this.\_service_name.function_name

### Login Component

1. Company details api

    ```
    this._user_management.company_details_by_name
    ```

    This api will fetch the company details from the company name provided in the parameter or dynamic segment in the url. If no company name present in params then it will store the company details as SUPER USER

2. Login api

    ```
    this._auth.login
    ```

    This api will login the user into the QMS app. There is a if else statement which will check if there is company name in params it will login the user respective to the company name else if company name is not added in the url params then it will login to SUPER USER.

3. User details api

    ```
    this._user_management.user_info
    ```

    this api will fetch the user information and store it in to local storage.

### Dashboard Component
