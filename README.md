# Keycloak Buildpack

Deploy [Keycloak] on Scalingo using this buildpack.


## Documentation

See the official tutorial:
👉 https://doc.scalingo.com/tutorials/keycloak


## Default Supported Version

The default Keycloak version deployed by this buildpack is specified in the
`KEYCLOAK_DEFAULT_VERSION` variable, which can be found in the [`VERSIONS`]
file.


## Maintenance Status

This buildpack is maintained by Scalingo solely for the deployment assets and
integration guidance provided in this repository and its associated
documentation.

Scalingo does not administer, manage, operate, or automatically upgrade
customer Keycloak instances.

Applying Keycloak upgrades and security patches remains the responsibility of
the customer by updating the `KEYCLOAK_VERSION` variable and redeploying the
application.

Should Scalingo discontinue maintenance of this buildpack or no longer
recommend its use, a notice period of at least six months will be provided
whenever feasible, except where immediate action is required due to security
concerns or external constraints.


[`VERSIONS`]: VERSIONS?plain=1#L3

[Keycloak]: https://keycloak.org/
