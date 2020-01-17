# Github

## (GH-100) One GitHub Organization

Code for all student GitHub projects must be stored in the Lambda School Labs Github organization: [https://github.com/Lambda-School-Labs](https://github.com/Lambda-School-Labs)

Rationale:

- Centralizing code into a single organization allows for easier management.

Exceptions:

- None

---

## (GH-101) Organization Roles

Lambda School staff and Section Leads will have the `Owner` role. All other organization members will have the `Member` role.

Rationale:

- Least privilege

Exceptions:

- None

---

## (GH-200) Dedicated GitHub Teams

Each project team will have their own dedicated GitHub team within the Lambda School Labs organization.

Rationale:

- Project specific teams allows for easier application of precise (least privilege) permissions as well as easier provisioning and deprovisioning as cohorts begin and end.

Exceptions:

- None

---

## (GH-201) GitHub Team Naming

GitHub project teams shall be created using the following convention:

- Name: `<Cohort> - <Product>`  (Example: `Labs 20 - Brew Plans`)

Rationale:

- GitHub teams have no mechanism for storing metadata, so the product name and cohort must be encoded in the team name.

Exceptions:

- None

---

## (GH-202) GitHub Team Roles

GitHub project team membership and team roles will be as follows:

- Section Lead ⇒ Maintainer
- Team Lead ⇒ Maintainer
- Student ⇒ Member

Rationale:

- Least privilege access

Exceptions:

- None

---

## (GH-300) GitHub Repo Naming

GitHub repos shall be named in all lowercase using the following convention:

- Name: <Product>-<Purpose>-<Postfix>
- The `Product` name can be stripped of special characters, shortened or otherwise made to be more readable, though it should remain consistent across repositories.
- The `Purpose` must be one of the following
    - `fe` for a front-end repository
    - `be` for a back-end repository
    - `ds` for a data science repository
    - `mobile` for a cross-platform mobile repository
    - `ios` for an iOS specific mobile repository
    - `android` for an Android specific mobile repository
    - `site` for a static website associated with the product
- The `Postfix` is an arbitrary string that can be appended when multiple repositories with the same purpose are require for a particular product.

Rationale:

- GitHub repositories have no mechanism for storing metadata, so the product name and purpose must be encoded in the repo name.

Exceptions:

- None

---

## (GH-310) GitHub Templates

All GitHub repositories must be created using one of the following templates:

- [https://github.com/Lambda-School-Labs/template-fe](https://github.com/Lambda-School-Labs/template-fe)
- [https://github.com/Lambda-School-Labs/template-be](https://github.com/Lambda-School-Labs/template-be)
- [https://github.com/Lambda-School-Labs/template-ds](https://github.com/Lambda-School-Labs/template-ds)
- [https://github.com/Lambda-School-Labs/template-android](https://github.com/Lambda-School-Labs/template-android)
- [https://github.com/Lambda-School-Labs/template-site](https://github.com/Lambda-School-Labs/template-site)

Rationale:

- Consistency is critical for managing a highly complex organization at scale. Starting from the same basic template helps to maintain this consistency.

Exceptions:

- None

---

## (GH-320) GitHub Repo Licensing

The README in the root of each GitHub repository must advertise that the code is maintained under the MIT license.

- There must be a file named LICENSE in the root of the directory using the MIT license format as described here: [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)
    - Use the year the project was created for the year
    - Use 'Lambda School' as the copyright holder

Rationale:

- Code written during Labs projects must be maintained as open-source so that it can be reference by hiring managers considering Lambda School students as candidates.
- The MIT license is very permissive and provides opportunities for student developed code to be reused and expanded by the open source community.

Exceptions:

- None

---

## (GH-330) GitHub Repo Badges

The README in the root of each GitHub repository must contain the following badges:

- Code Climate Maintainability
    - [https://codeclimate.com/github/codeclimate/codeclimate/badges](https://codeclimate.com/github/codeclimate/codeclimate/badges)
- Code Climate Test Coverage
    - [https://codeclimate.com/github/codeclimate/codeclimate/badges](https://codeclimate.com/github/codeclimate/codeclimate/badges)

Rationale:

- Code Climate is the standard system for ensuring quality across all Labs products. Displaying a badge front and center in a repo is important to maintain visibility into the state of the codebase.

Exceptions:

- Any repository with code that is not supported by Code Climate