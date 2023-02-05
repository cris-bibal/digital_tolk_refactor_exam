Good Code:
1). Used Repo Pattern
2). Used Dependency and Method Injection
3). Namespacing is Ok
3). Almost of method/function in BookingController are good except for "distanceFeed()".
4). Business logic are placed in the Repository class


Bad Code:
1). The "distanceFeed()" method/function in BookingController is too long, it should be moved in Repository Class, it must follow the Single Responsibility Principle
2). There are redundant codes in BookingRepository
3). There are functions with 100+ lines, it is difficult to debug once there is a bug/issues in the code.
4). So many "else" statement in BookingRepository.
5). SOLID Principles is not fully applied in the code.
6). Some variables are not declared properly.
