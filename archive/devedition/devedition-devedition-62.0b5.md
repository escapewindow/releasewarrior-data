# devedition 62.0b5

### Date of go-to-build: 2018-07-02

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/IO1RufPdQVCe7YN5QbgFaA) IO1RufPdQVCe7YN5QbgFaA
* [push](https://tools.taskcluster.net/push-inspector/#/Z8skbrxORMaRhwSmuKyrFg) Z8skbrxORMaRhwSmuKyrFg
* [ship](https://tools.taskcluster.net/push-inspector/#/P-s3q0AiRJqvpeIl3NV3VA) P-s3q0AiRJqvpeIl3NV3VA
```
export PROMOTE_TASK_ID=IO1RufPdQVCe7YN5QbgFaA
export PUSH_TASK_ID=Z8skbrxORMaRhwSmuKyrFg
export SHIP_TASK_ID=P-s3q0AiRJqvpeIl3NV3VA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1472926](https://bugzil.la/1472926)        | partials-as-linux64-devedition-nightly/opt - WMSMEMfQQKCU2IuTa3JDzQ failed.  `construct.core.ConstError: parsing expected b'MAR1' but parsed b'<?xm'` rerunning | True | True |

