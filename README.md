# Overview

This layer provides the base for legacy OpenStack charms, avoiding the
requirement to ship a copy of charm-helpers directly in the codebase
for each and every charm.

This layer will ensure that charmhelpers are installed on the target
system for use by the charm prior to execution of any charm hook code.
