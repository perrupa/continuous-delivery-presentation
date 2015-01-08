
# Continuous Delivery Rollout

---

## This will be a step-by-step process

---

## Stage 1

- Full test automation (Late January)

- Git Flow (Early March)

- Push w/o downtime (Mid-March)

- Stable hotfixes (Mid-March)

- Feature Flags (Early April)

---

## Stage 2

- Deployment script: revisited

- Improved Build Server (Mid-April)

- Deploys faster than ___ minutes (Early May)

- Recent Activity and P2P in SOA (Late May - Early June)

- Hands-off Deploys (June)


---

## Stage 3

- Revived Achievers Tech Culture (June)

- Greater Unit test coverage (110%) (Mid-June)

- Beta Flags (comparison tests, A/B Tests, etc) (Late June)

- Full Stack developers (Mid-July)

- Platform knowledge of all devs in 2/3 for 70% of platform areas (August)

---

# Stage 1

---

## Full test automation 
####(Late January)

- Run unit tests for each commit on Master and Develop 
- Trigger regression tests /X days

---

## Git Flow 
####(February)

- Have a definition of "Ready for Release" 
- GIT lunch and learn 
- Source Pull-Request software 
- Have Pull Request process 

---

## Push w/o downtime 
####(Mid-March)

- Remove DB locking for Alters 
	- Alternatively, separate data migrations from deploys
- Solution for Alter-replication 

---

## Stable hotfixes 
####(Mid-March)

- Files Changed Report (daily? per-release?) 
- Dependency b/w repo and unit tests (what did we mean? no pushes when tests fail?) 
- Test Coverage calculated automatically 

---

# Discussion