# List of projects scala-steward should care about
#- open-electrons/open-electrons-templates
#- open-electrons/eMSP-platform
#- open-electrons/open-electrons-infra
#- open-electrons/cpo-platform/ocpp-gateway-server
#- open-electrons/cpo-platform/cpo-platform-server
#- open-electrons/cpo-platform/cpo-platform-flyway-migrations
#- open-electrons/ocpp-scala
#- open-electrons/ocpi-scala
#- open-electrons/oscp-scala

# For the `open-electrons/cpo-platform` repository, we target both the root and specific subprojects
repos = [
  {
    repo = "open-electrons/cpo-platform"
    buildRoots = [ ".", "ocpp-gateway-server", "cpo-platform-server", "cpo-platform-flyway-migrations" ]
  },
  {
    repo = "open-electrons/open-electrons-templates"
    buildRoots = [ "." ] # Only root project
  },
  {
    repo = "open-electrons/eMSP-platform"
    buildRoots = [ "." ] # Only root project
  },
  {
    repo = "open-electrons/open-electrons-infra"
    buildRoots = [ "." ] # Only root project
  },
  {
    repo = "open-electrons/ocpp-scala"
    buildRoots = [ "." ] # Only root project
  },
  {
    repo = "open-electrons/ocpi-scala"
    buildRoots = [ "." ] # Only root project
  },
  {
    repo = "open-electrons/oscp-scala"
    buildRoots = [ "." ] # Only root project
  }
]
