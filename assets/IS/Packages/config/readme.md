The folder "config" in the "Packages" folder is necessary/mandatory so that ABE creates the isconfiguration composites, which are a prerequisite for variable substitution of IS assets like ports, JDBC adapters etc.
Note: ABE (or rather the ABE IS Plugin) creates default files in this folder at runtime if these files are not existing. This is expected. Place files like acls.cnf etc. in here from the IntegrationServer/instances/default/config folder as required (see Deployer documentation).