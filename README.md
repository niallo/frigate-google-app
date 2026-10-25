# Frigate Nest Cameras

Frigate Nest Cameras is a personal integration that connects selected Google Nest camera live streams to a privately operated Frigate video recorder. It is not a public service and does not accept registrations.

## Privacy policy

Last updated October 24, 2026.

The integration requests Google Nest device access only for the cameras selected during Google authorization. It uses live video and audio and the home/device information that Google requires to identify those cameras. It does not request Gmail, Google Photos, Google Drive, thermostat control, or access to unselected cameras.

Camera streams are processed and recordings are stored on the operator's private server. Authorized users can view them through the private Frigate interface. Google supplies the camera streams and processes authorization requests under Google's own policies. This integration does not sell personal information, use camera data for advertising, or use it to train general-purpose AI models.

Recording retention is controlled by the private recorder's settings. Recordings are currently retained for seven days, unless the operator explicitly exports a clip for longer storage. Cloud video uploads are currently disabled. Any future backup destination requires separate configuration and authorization.

Google credentials are stored in restricted files on the private server. Access can be revoked through Google Account connections or Google Nest Partner Connections Manager. Revoking access stops future camera access; existing local recordings remain subject to the recorder's retention settings or manual deletion.

This app is operated for personal use by the owner of this GitHub repository. Privacy questions can be directed to the operator through this repository's issue tracker. Do not post camera footage, credentials, home addresses or other private information in public issues.
