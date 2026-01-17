# Med Monitor App

Angular-based frontend for MedMonitorApp, providing dashboards, patient detail views, alert management, and user profile integration.

## Features

- Dashboard for patient vital signs and alerts
- Patient detail view with real-time data
- Alert listing and retrieval
- User authentication via MSAL (Azure AD)
- Responsive navigation bar

## Stack

- Angular 18
- RxJS
- MSAL (Azure AD authentication)
- Tailwind CSS (styling)

## Preview

![App Preview](https://res.cloudinary.com/dtfzj5caw/image/upload/v1768613189/github-repos/med-monitor-app/1_qzeb0v.webp)

## Structure

```text
app/
  components/
    dashboard/
    failed/
    navbar/
    patient-detail/
    profile/
  models/
  services/
    alert/
    patient/
    server/
  auth/
  environments/
```

## Best Practices

- Modular component design
- Services for API integration and business logic
- Environment-based configuration
- Clear separation of concerns
- Unit tests for services and components
