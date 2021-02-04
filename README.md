# ohtup-staging

This staging server is meant to support application development during University of Helsinki *ohjelmistotuotantoprojekti* course.

## Instructions of use

- Read the `README` file at `/home/ohtup_user`.
- **Only** use the user `ohtup_user`.
- Put all of your group's stuff in your own folder located `/home/ohtup_user`.
- If you need to configure the shared `nginx` server, see `/home/ohtup_user/nginx/README`.
- *Be mindful of other users, this is a shared machine!*

## SSH Access

The server is accessible only through the university's public SSH servers, i.e., `melkki`, `melkinpaasi`, etc.

###### Log on `ohtup-staging` server via SSH

```bash
ssh -J melkinpaasi.cs.helsinki.fi ohtup-staging.cs.helsinki.fi
```

## Shared user account

**Always** use the shared user account `ohtup_user`.

###### Switch to shared user account

```bash
./login.sh
```

## Currently active apps:

- Assembler - https://ohtup-staging.cs.helsinki.fi/assembler/
