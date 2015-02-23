
# Juggernaut - Realdoc Document (ECM) Micro Service  

Juggernaut (ECM Microservice) provides RESTful endpoints for performing document lifecycle actions such as creation, metadata-modification, version management, states, etc to Realdoc Vault documents.

§ For changes and known-issues refer to `release-notes.txt`.
§ For deployment details refer to `HOWTO.txt`.

## RESTful Endpoints:
    +-------------------------------+--------+----------------------------------+------------------+---------+
    | API                           | Method | Consumes                         | Produces         | Status  |
    +-------------------------------+--------+----------------------------------+------------------+---------+
    | createDocument                | POST   | application/json                 | application/json | Working |
    | getDocument                   | GET    | application/json                 | application/json | Working |
    | addDocMetadata                | POST   | application/json                 | application/json | Working |
    | updateDocMetadata             | PATCH  | application/json                 | application/json | Working |
    | getDocTypes                   | GET    | application/json                 | application/json | Working |
    | delete                        | DELETE | application/json                 | application/json | Working |
    | createSingleFileDocument      | POST   | multipart/form-data              | application/json | Working |
    | createMultipleFileDocument    | POST   | multipart/form-data              | application/json | Working |
    | addDocumentVersion            | POST   |[multipart/form-data              | application/json | Working |
    | getDocumentActiveVersionFiles | GET    | application/json                 | application/json | Working |
    +----------------------------...+--------+----------------------------------+------------------+---------+
