# 1. User

ENDPOINT                     | DESCRIPTION
-----------------------------|--------------------------------------------
GET    /api/users           | Retrieve all users
GET    /api/users/{id}      | Retrieve a single user by ID
POST   /api/users           | Create a new user
PUT    /api/users/{id}      | Fully update an existing user by ID
PATCH  /api/users/{id}      | Partially update an existing user by ID
DELETE /api/users/{id}      | Remove an existing user by ID

#2. UserType

ENDPOINT                           | DESCRIPTION
-----------------------------------|---------------------------------------------
GET    /api/user-types            | Retrieve all user types
GET    /api/user-types/{id}       | Retrieve a single user type by ID
POST   /api/user-types            | Create a new user type
PUT    /api/user-types/{id}       | Fully update an existing user type by ID
PATCH  /api/user-types/{id}       | Partially update an existing user type by ID
DELETE /api/user-types/{id}       | Remove an existing user type by ID

# 3. Organization

ENDPOINT                              | DESCRIPTION
--------------------------------------|--------------------------------------------
GET    /api/organizations            | Retrieve all organizations
GET    /api/organizations/{id}       | Retrieve a single organization by ID
POST   /api/organizations            | Create a new organization
PUT    /api/organizations/{id}       | Fully update an existing organization by ID
PATCH  /api/organizations/{id}       | Partially update an existing organization by ID
DELETE /api/organizations/{id}       | Remove an existing organization by ID

# 4. Team

ENDPOINT                      | DESCRIPTION
------------------------------|--------------------------------------------
GET    /api/teams            | Retrieve all teams
GET    /api/teams/{id}       | Retrieve a single team by ID
POST   /api/teams            | Create a new team
PUT    /api/teams/{id}       | Fully update an existing team by ID
PATCH  /api/teams/{id}       | Partially update an existing team by ID
DELETE /api/teams/{id}       | Remove an existing team by ID

# 5. UserTeam 

ENDPOINT                                | DESCRIPTION
----------------------------------------|------------------------------------------------------
GET    /api/user-teams                 | Retrieve all user-team relationships
GET    /api/user-teams/{userId}/{teamId}  | Retrieve a single relationship by User + Team IDs
POST   /api/user-teams                 | Create a new user-team relationship
PUT    /api/user-teams/{userId}/{teamId}   | Fully update an existing relationship
PATCH  /api/user-teams/{userId}/{teamId}   | Partially update an existing relationship
DELETE /api/user-teams/{userId}/{teamId}   | Remove an existing user-team relationship

# 6. Workspace

ENDPOINT                        | DESCRIPTION
--------------------------------|--------------------------------------------
GET    /api/workspaces          | Retrieve all workspaces
GET    /api/workspaces/{id}     | Retrieve a single workspace by ID
POST   /api/workspaces          | Create a new workspace
PUT    /api/workspaces/{id}     | Fully update an existing workspace by ID
PATCH  /api/workspaces/{id}     | Partially update an existing workspace by ID
DELETE /api/workspaces/{id}     | Remove an existing workspace by ID

# 7. WorkspaceHistory

ENDPOINT                                 | DESCRIPTION
-----------------------------------------|--------------------------------------------
GET    /api/workspace-histories         | Retrieve all workspace history entries
GET    /api/workspace-histories/{id}    | Retrieve a single workspace history entry by ID
POST   /api/workspace-histories         | Create a new workspace history entry
PUT    /api/workspace-histories/{id}    | Fully update an existing workspace history entry
PATCH  /api/workspace-histories/{id}    | Partially update an existing workspace history entry
DELETE /api/workspace-histories/{id}    | Remove an existing workspace history entry

# 8. Permit

ENDPOINT                      | DESCRIPTION
------------------------------|--------------------------------------------
GET    /api/permits          | Retrieve all permits
GET    /api/permits/{id}     | Retrieve a single permit by ID
POST   /api/permits          | Create a new permit
PUT    /api/permits/{id}     | Fully update an existing permit
PATCH  /api/permits/{id}     | Partially update an existing permit
DELETE /api/permits/{id}     | Remove an existing permit

# 9. MetadataSearch

ENDPOINT                          | DESCRIPTION
----------------------------------|---------------------------------------------
GET    /api/metadata-searches     | Retrieve all metadata search records
GET    /api/metadata-searches/{id}| Retrieve a single metadata search record by ID
POST   /api/metadata-searches     | Create a new metadata search record
PUT    /api/metadata-searches/{id}| Fully update an existing metadata search record
PATCH  /api/metadata-searches/{id}| Partially update an existing metadata search record
DELETE /api/metadata-searches/{id}| Remove an existing metadata search record

# 10. Analysis

ENDPOINT                       | DESCRIPTION
-------------------------------|--------------------------------------------
GET    /api/analyses           | Retrieve all analyses
GET    /api/analyses/{id}      | Retrieve a single analysis by ID
POST   /api/analyses           | Create a new analysis
PUT    /api/analyses/{id}      | Fully update an existing analysis
PATCH  /api/analyses/{id}      | Partially update an existing analysis
DELETE /api/analyses/{id}      | Remove an existing analysis

# 11. Cohort

ENDPOINT                     | DESCRIPTION
-----------------------------|--------------------------------------------
GET    /api/cohorts         | Retrieve all cohorts
GET    /api/cohorts/{id}    | Retrieve a single cohort by ID
POST   /api/cohorts         | Create a new cohort
PUT    /api/cohorts/{id}    | Fully update an existing cohort
PATCH  /api/cohorts/{id}    | Partially update an existing cohort
DELETE /api/cohorts/{id}    | Remove an existing cohort

# 12. CohortResult 

ENDPOINT                                 | DESCRIPTION
-----------------------------------------|-------------------------------------------------------
GET    /api/cohort-results              | Retrieve all cohort-results
GET    /api/cohort-results/{cohortId}/{dataId} | Retrieve a single cohort-result by Cohort + Data IDs
POST   /api/cohort-results              | Create a new cohort-result
PUT    /api/cohort-results/{cohortId}/{dataId}  | Fully update an existing cohort-result
PATCH  /api/cohort-results/{cohortId}/{dataId}  | Partially update an existing cohort-result
DELETE /api/cohort-results/{cohortId}/{dataId}  | Remove an existing cohort-result

# 13. Algorithm

ENDPOINT                        | DESCRIPTION
--------------------------------|--------------------------------------------
GET    /api/algorithms          | Retrieve all algorithms
GET    /api/algorithms/{id}     | Retrieve a single algorithm by ID
POST   /api/algorithms          | Create a new algorithm
PUT    /api/algorithms/{id}     | Fully update an existing algorithm
PATCH  /api/algorithms/{id}     | Partially update an existing algorithm
DELETE /api/algorithms/{id}     | Remove an existing algorithm

# 14. CohortAlgorithm 

ENDPOINT                                        | DESCRIPTION
------------------------------------------------|---------------------------------------------------------
GET    /api/cohort-algorithms                  | Retrieve all cohort-algorithm relationships
GET    /api/cohort-algorithms/{cohortId}/{algorithmId} | Retrieve a single relationship by Cohort + Algorithm IDs
POST   /api/cohort-algorithms                  | Create a new cohort-algorithm relationship
PUT    /api/cohort-algorithms/{cohortId}/{algorithmId}   | Fully update an existing cohort-algorithm relationship
PATCH  /api/cohort-algorithms/{cohortId}/{algorithmId}   | Partially update an existing cohort-algorithm relationship
DELETE /api/cohort-algorithms/{cohortId}/{algorithmId}   | Remove an existing cohort-algor