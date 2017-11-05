<a href="https://ibm.biz/gramps-graphql"><img src="https://gramps-graphql.github.io/gramps-express/assets/img/gramps-banner.png" alt="GrAMPS · An easier way to manage the data sources powering your GraphQL server" width="450"></a>

# GrAMPS GraphQL Error Handling
[![license](https://img.shields.io/npm/l/@gramps/errors.svg)](https://github.com/gramps-graphql/gramps-errors/blob/master/LICENSE) [![npm version](https://img.shields.io/npm/v/@gramps/errors.svg?style=flat)](https://www.npmjs.com/package/@gramps/errors) [![Build Status](https://travis-ci.org/gramps-graphql/gramps-errors.svg?branch=master)](https://travis-ci.org/gramps-graphql/gramps-errors) [![Maintainability](https://api.codeclimate.com/v1/badges/ac264833fac1fbd1afe0/maintainability)](https://codeclimate.com/github/gramps-graphql/gramps-errors/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/ac264833fac1fbd1afe0/test_coverage)](https://codeclimate.com/github/gramps-graphql/gramps-errors/test_coverage) [![Greenkeeper badge](https://badges.greenkeeper.io/gramps-graphql/gramps-errors.svg)](https://greenkeeper.io/)

**An easier way to manage the data sources powering your GraphQL server.**

**GrAMPS** (short for **Gr**aphQL **A**pollo **M**icroservice **P**attern **S**erver) is middleware designed for [apollo-server-express](https://git.io/vd1wc) that allows independent data sources — a schema, resolvers, and data access model — to be composed into a single GraphQL schema, while keeping the code within each data source isolated, independently testable, and completely decoupled from the rest of your application.

## Developer Quickstart

[See the 5-minute quickstart in our documentation.](https://gramps-graphql.github.io/gramps-express/overview/quickstart/)

## Credits

GrAMPS was born at [IBM Cloud](https://www.ibm.com/cloud-computing/) to solve the problem of maintaining a single GraphQL endpoint in a µ-service architecture where data sources are owned by dozens of teams.

We’re releasing it under the MIT license because we ❤️ the developer community.
