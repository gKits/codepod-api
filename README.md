# codepod-api
The API for the Codepod Project

### Routes

...Implemantation TBD...

- Pods
  - `GET /pods/`
    - Returns all Pods of the Requesting user
  - `GET /pods/<podId>/`
    - Returns Pod with the given ID
    - Pod needs to belong to the requesting User
  - `POST /pods/<podId>/`
    - Creates a Pod with the given ID
    - ID has to be unique
    - Request Body holds Pod configuration
  - `DELETE /pods/<podId>?key=<key>`
    - Deletes the Pod with the given ID
    - Pod needs to belong to the requesting User
    - Param key is needed to delete the Pod
