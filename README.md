# SFDX Commands :wolf: :computer:

* sfdx force --help
* sfdx force:doc:commands:list
* sfdx force:auth:web:login
* sfdx force:org:open -u DevHub
* sfdx force:auth:web:login -r https://test.salesforce.com -a FullSandbox
* sfdx force:auth:web:login -r https://test.salesforce.com -a DevSandbox
* sfdx force:org:open -u FullSandbox
* sfdx force:org:open -u MyScratchOrg
* sfdx force:limits:api:display -u DevSandbox
* sfdx force:org:list --verbose       # see all orgs
* sfdx force:project:create -n geolocation
* sfdx force:org:create -s -f config/project-scratch-def.json -a GeoAppScratch # create a scratch with alias GeoAppScratch


#

  * force:alias:list                   # list username aliases for sfdx
  * force:alias:set                    # set username aliases for sfdx
  * force:apex:class:create            # create an apex class
  * force:apex:execute                 # execute anonymous apex code
  * force:apex:log:get                 # fetch a debug log
  * force:apex:log:list                # list debug logs
  * force:apex:test:report             # display test results
  * force:apex:test:run                # invoke apex tests
  * force:auth:jwt:grant               # authorize an org using the jwt flow
  * force:auth:sfdxurl:store           # authorize an org using an sfdx auth url
  * force:auth:web:login               # authorize an org using the web login flow
  * force:config:get                   # get config var value(s) for given name(s)
  * force:config:list                  # list config vars for sfdx
  * force:config:set                   # set config vars for sfdx
  * force:data:bulk:delete             # bulk delete records from a csv file
  * force:data:bulk:status             # view the status of a bulk data load job or batch
  * force:data:bulk:upsert             # bulk upsert records from a csv file
  * force:data:record:create           # create a record
  * force:data:record:delete           # delete a record
  * force:data:record:get              # view a record
  * force:data:record:update           # update a record
  * force:data:soql:query              # execute a soql query
  * force:data:tree:export             # export data from an org into sobject tree format for force:data:tree:import consumption
  * force:data:tree:import             # import data into an org using sobject tree api
  * force:doc:commands:display         # display help for force commands
  * force:doc:commands:list            # list the force commands
  * force:lightning:app:create         # create a lightning app
  * force:lightning:component:create   # create a lightning component
  * force:lightning:event:create       # create a lightning event
  * force:lightning:interface:create   # create a lightning interface
  * force:lightning:lint               # Linter for Lightning Components
  * force:lightning:test:create        # create a lightning test
  * force:lightning:test:run           # invoke lightning component tests
  * force:limits:api:display           # display current org’s limits
  * force:mdapi:convert                # convert metadata api source into the sfdx source format
  * force:mdapi:deploy                 # deploys metadata to an org using metadata api
  * force:mdapi:retrieve               # retrieves metadata from an org using metadata api
  * force:org:create                   # create a scratch org
  * force:org:delete                   # mark a scratch org for deletion
  * force:org:display                  # get org description
  * force:org:list                     # list all active orgs you’ve created or authenticated to
  * force:org:open                     # open an org in your browser
  * force:package1:version:create      # create a new package version in the release org
  * force:package1:version:create:get  # retrieve status of package upload request
  * force:package1:version:display     # display details about a package version
  * force:package1:version:list        # list package versions for the specified package or for the org
  * force:package2:create              # create a package2
  * force:package2:installed:list      # list the org’s installed subscriber package2 versions
  * force:package2:list                # list all package2 packages in the dev hub org
  * force:package2:manifest:create     # create a manifest for the package2 from the specified directory
  * force:package2:members:list        # list all subscriber package2 members in the org
  * force:package2:version:create      # create a package2 version in the dev hub org
  * force:package2:version:create:get  # retrieve a package2 version creation request in the dev hub org
  * force:package2:version:create:list # list package2 version creation requests in the dev hub org
  * force:package2:version:get         # retrieve a package version in the dev hub org
  * force:package2:version:install     # install a subscriber package2 version
  * force:package2:version:list        # list all package2 versions in the dev hub org
  * force:package2:version:uninstall   # uninstall a subscriber package2 version
  * force:package2:version:update      # update a package2 version in the dev hub org
  * force:package:install              # install a package in the target org
  * force:package:install:get          # retrieve status of package install request
  * force:project:create               # create a new SFDX project
  * force:project:upgrade              # update project config files to the latest format
  * force:schema:sobject:describe      # describe an object
  * force:schema:sobject:list          # list all objects of a type
  * force:source:convert               # convert sfdx source into the metadata api source format
  * force:source:open                  # edit a lightning page with lightning app builder
  * force:source:pull                  # pull source from the scratch org to the project
  * force:source:push                  # push source to an org from the project
  * force:source:status                # list local changes and/or changes in a scratch org
  * force:user:password:generate       # generate a password for a scratch org
  * force:user:permset:assign          # assign a permission set to the admin user of an org
  * force:visualforce:component:create # create a visualforce component
  * force:visualforce:page:create      # create a visualforce page


:package:
:apple:
