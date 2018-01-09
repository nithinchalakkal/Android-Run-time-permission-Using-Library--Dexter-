Here, we are going to simplify the process of adding the runtime permissions using Dexter library. Using this library, the permissions can be implemented in seconds.

Requesting Single Permission
To request a single permission, you can use withPermission() method by passing the required permission. You also need a PermissionListener callback to receive the state of the permission.

> onPermissionGranted() will be called once the permission is granted.

> onPermissionDenied() will be called when the permission is denied. Here you can check whether the permission is permanently denied by using response.isPermanentlyDenied() condition.




