## Elide OSGi Wrapper

Wraps the outstanding [Elide](https://elide.io/) library into an OSGi bundle.

Elide enables you to stand up a JSON API or GraphQL web service with minimal effort starting from a JPA annotated data model.    Using it in an OSGi container along with PAX-JPA and PAX Whiteboard makes it trivial to stand-up CRUD style APIs.

However Elide has quite a few external dependencies this bundle pom.xml wraps those into a single OSGi bundle and also provides a Karaf feature to make deployment to Karaf easy.
