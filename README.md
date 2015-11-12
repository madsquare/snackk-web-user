# snackk-web-api-user

## require
* lodash


## functions
user:
* registUser
* loadMe
* updateUser
* deleteUser

provider:
* addProvider
* deleteProvider

profile:
* updateProfile
* deleteProfile
* loadDefaultProfile

password:
* updatePassword

validate:
* validateEmail

verify:
* sendVerifyEmail




### validate email ERROR CODE
```
DUPLICATED: 'error_duplicated'
INVALID: 'error_invalid'
UN_KNOWN: 'error_unknown'
```

## example
```
userCtr.init server
userCtr.loadMe {
  'success': (res) =>
    debugger
  'error': (er) =>
    debugger
}
```
