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

# 4. Workspace

ENDPOINT                        | DESCRIPTION
--------------------------------|--------------------------------------------
GET    /api/workspaces          | Retrieve all workspaces
GET    /api/workspaces/{id}     | Retrieve a single workspace by ID
POST   /api/workspaces          | Create a new workspace
PUT    /api/workspaces/{id}     | Fully update an existing workspace by ID
PATCH  /api/workspaces/{id}     | Partially update an existing workspace by ID
DELETE /api/workspaces/{id}     | Remove an existing workspace by ID

# 5. WorkspaceHistory

ENDPOINT                                 | DESCRIPTION
-----------------------------------------|--------------------------------------------
GET    /api/workspace-histories         | Retrieve all workspace history entries
GET    /api/workspace-histories/{id}    | Retrieve a single workspace history entry by ID
POST   /api/workspace-histories         | Create a new workspace history entry
PUT    /api/workspace-histories/{id}    | Fully update an existing workspace history entry
PATCH  /api/workspace-histories/{id}    | Partially update an existing workspace history entry
DELETE /api/workspace-histories/{id}    | Remove an existing workspace history entry

# 6. Permit

ENDPOINT                      | DESCRIPTION
------------------------------|--------------------------------------------
GET    /api/permits          | Retrieve all permits
GET    /api/permits/{id}     | Retrieve a single permit by ID
POST   /api/permits          | Create a new permit
PUT    /api/permits/{id}     | Fully update an existing permit
PATCH  /api/permits/{id}     | Partially update an existing permit
DELETE /api/permits/{id}     | Remove an existing permit

# 7. MetadataSearch

ENDPOINT                          | DESCRIPTION
----------------------------------|---------------------------------------------
GET    /api/metadata-searches     | Retrieve all metadata search records
GET    /api/metadata-searches/{id}| Retrieve a single metadata search record by ID
POST   /api/metadata-searches     | Create a new metadata search record
PUT    /api/metadata-searches/{id}| Fully update an existing metadata search record
PATCH  /api/metadata-searches/{id}| Partially update an existing metadata search record
DELETE /api/metadata-searches/{id}| Remove an existing metadata search record

# 8. Analysis

ENDPOINT                       | DESCRIPTION
-------------------------------|--------------------------------------------
GET    /api/analyses           | Retrieve all analyses
GET    /api/analyses/{id}      | Retrieve a single analysis by ID
POST   /api/analyses           | Create a new analysis
PUT    /api/analyses/{id}      | Fully update an existing analysis
PATCH  /api/analyses/{id}      | Partially update an existing analysis
DELETE /api/analyses/{id}      | Remove an existing analysis

# 9. Cohort

ENDPOINT                     | DESCRIPTION
-----------------------------|--------------------------------------------
GET    /api/cohorts         | Retrieve all cohorts
GET    /api/cohorts/{id}    | Retrieve a single cohort by ID
POST   /api/cohorts         | Create a new cohort
PUT    /api/cohorts/{id}    | Fully update an existing cohort
PATCH  /api/cohorts/{id}    | Partially update an existing cohort
DELETE /api/cohorts/{id}    | Remove an existing cohort

# 10. CohortResult 

ENDPOINT                                 | DESCRIPTION
-----------------------------------------|-------------------------------------------------------
GET    /api/cohort-results              | Retrieve all cohort-results
GET    /api/cohort-results/{cohortId}/{dataId} | Retrieve a single cohort-result by Cohort + Data IDs
POST   /api/cohort-results              | Create a new cohort-result
PUT    /api/cohort-results/{cohortId}/{dataId}  | Fully update an existing cohort-result
PATCH  /api/cohort-results/{cohortId}/{dataId}  | Partially update an existing cohort-result
DELETE /api/cohort-results/{cohortId}/{dataId}  | Remove an existing cohort-result

# 11. Algorithm

ENDPOINT                        | DESCRIPTION
--------------------------------|--------------------------------------------
GET    /api/algorithms          | Retrieve all algorithms
GET    /api/algorithms/{id}     | Retrieve a single algorithm by ID
POST   /api/algorithms          | Create a new algorithm
PUT    /api/algorithms/{id}     | Fully update an existing algorithm
PATCH  /api/algorithms/{id}     | Partially update an existing algorithm
DELETE /api/algorithms/{id}     | Remove an existing algorithm

# 12. CohortAlgorithm

ENDPOINT                                        | DESCRIPTION
------------------------------------------------|---------------------------------------------------------
GET    /api/cohort-algorithms                  | Retrieve all cohort-algorithm relationships
GET    /api/cohort-algorithms/{cohortId}/{algorithmId} | Retrieve a single relationship by Cohort + Algorithm IDs
POST   /api/cohort-algorithms                  | Create a new cohort-algorithm relationship
PUT    /api/cohort-algorithms/{cohortId}/{algorithmId}   | Fully update an existing cohort-algorithm relationship
PATCH  /api/cohort-algorithms/{cohortId}/{algorithmId}   | Partially update an existing cohort-algorithm relationship
DELETE /api/cohort-algorithms/{cohortId}/{algorithmId}   | Remove an existing cohort-algor