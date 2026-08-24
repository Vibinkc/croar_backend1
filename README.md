# Croar Backend — SonarQube source

Analysis-only mirror of the Croar backend. Contains just the application
source that `sonar-project.properties` scans (`sonar.sources=app`), plus the
dependency manifests Sonar uses for context.

Not a deployable checkout: no secrets, migrations, scripts, uploads or infra.
