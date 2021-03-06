# firefox 52.8.1esr

### Date of go-to-build: 2018-06-05

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Ucpd12G2Qg-1OHRoqpUtuQ) Ucpd12G2Qg-1OHRoqpUtuQ
```
export PROMOTE_TASK_ID=Ucpd12G2Qg-1OHRoqpUtuQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#1-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-publish-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1467002](https://bugzil.la/1467002)        | broken releaserunner virtualenv blocks release start | True | True |
| jlund  | 2 | [bug none](https://bugzil.la/none)        | releaserunner evaluating wrong taskid from taskcluster route while trying to find ci builds. graph not submitting. trying to restart releaserunner in hopes it's a caching thing as latest manual request shows correct taskid. see #releaseduty for context | True | True |
| nthomas  | 3 | [bug 1467067](https://bugzil.la/1467067)        | mar and source signing failures | True | False |
| nthomas  | 4 | [bug 1467078](https://bugzil.la/1467078)        | buildbot bridge not transferring buildbot job status to TC | True | False |
| bhearsum  | 5 | [bug 1461490](https://bugzil.la/1461490)        | windows update verify failed - https://gist.github.com/mozbhearsum/f827a919707445bbb0ced6884f761d7f for helper script | True | True |

