# Getting started with SID Forge

## Before you begin

- Create a tested full-system backup or virtual-machine snapshot.
- Finish pending Windows updates and restart if required.
- Make sure no other users remain signed in.
- Review BitLocker, encrypted files, domain membership, and application-specific requirements.
- Do not use a Machine SID change as a general-purpose repair without diagnosis.

## Start the operation

1. Download SID Forge only from `https://sidforge.pp.ua/`.
2. Approve the Windows administrator prompt.
3. Review the inspection summary and the current and proposed Machine SID.
4. Complete the account authorization shown by SID Forge.
5. Confirm only when the computer is ready to restart.

## During restart

- Do not power off the computer.
- Do not sign in while the protected stage is still running.
- Follow the full-screen status and wait for completion.

## After sign-in

SID Forge shows a separate result with the completed state, previous SID, current SID, and diagnostic information when needed.

If the operation reports an error, do not immediately repeat it. Record the diagnostic ID and contact `support@sidforge.pp.ua`.
