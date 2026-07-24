# SID Forge use cases and limitations

## Appropriate scenarios

SID Forge is intended for an existing Windows installation that requires a controlled local Machine SID change after cloning, restoration, redeployment, or hardware replacement.

Common operator goals include:

- giving cloned PCs distinct local Machine SIDs;
- retaining configured local profiles and applications;
- avoiding a full reinstall for a supported identity-change task;
- receiving a verified old-to-new SID result after restart.

## Diagnose before changing a SID

Several Windows identifiers can be duplicated after cloning. Machine SID, computer name, domain computer account, MachineGuid, management identifiers, update-service identifiers, activation state, and distributed-transaction identity are not interchangeable.

SID Forge changes the local Machine SID and the supported Windows references that depend on it. It should not be presented as a universal repair for every clone-related symptom.

## When not to proceed

- The computer is a domain controller.
- A backup or snapshot is unavailable.
- Windows updates or another repair operation are pending.
- Disk encryption or protected data has not been reviewed.
- The operator cannot allow the required restart to complete uninterrupted.

For questions about a specific environment, contact `support@sidforge.pp.ua` before starting.
