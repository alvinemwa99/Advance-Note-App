# Architecture
## This project uses MVVM architecture 
### Reason:

#### -more clear and intentional separation of concerns
#### -single source of truth for our UI state 
#### -simpler and more direct UI testability, since we can define how the UI should look like
# Packaging Structure
## *data
### handles getting and mutating data from needed sources
## *di
### handles dependency injection 
## *domain
### handles encasing business logic for reuse
## *presentation
### handles displaying data on the device
