# Accessibility

Accessibility matters because the Student Pass System is used by students, teachers, and wardens to manage outing requests. Everyone should be able to submit, review, and approve passes without facing barriers caused by technology, design, or accessibility limitations.

We are committed to creating an experience that is usable by people with different abilities, devices, and levels of technical experience. This document outlines our accessibility priorities, contributor expectations, reporting process, and ongoing improvement efforts.

## Priorities

The Student Pass System supports a simple but important workflow:

1. Students submit outing requests.
2. Teachers or wardens review requests.
3. Requests are approved or rejected.
4. Students receive status updates.

To ensure these tasks remain accessible, we prioritize:

- Keyboard navigation for all major features.
- Screen reader support for forms and request details.
- Clear labels and instructions on all input fields.
- Readable text with sufficient contrast.
- Responsive layouts for desktop and mobile devices.
- Clear status indicators for approved, pending, and rejected requests.
- Helpful error messages that explain how to correct mistakes.

Accessibility improvements are continuously reviewed as the project evolves.

## Contributor Expectations

All contributors should consider accessibility when designing, developing, and maintaining features.

Contributors are expected to:

- Use semantic HTML elements whenever possible.
- Ensure forms have visible labels.
- Provide descriptive text for buttons and actions.
- Include alternative text for meaningful images.
- Ensure all functionality can be completed using only a keyboard.
- Avoid communicating information using color alone.
- Maintain readability on different screen sizes.
- Test any user-facing changes before submitting them.

When submitting pull requests, contributors should include:

- A summary of accessibility considerations.
- Any accessibility testing performed.
- Notes on any known limitations introduced by the change.

## Reporting Accessibility Issues

If you encounter an accessibility problem while using the Student Pass System, please report it through the project's issue tracker.

Helpful information includes:

- The page or feature where the issue occurred.
- The task you were attempting to perform.
- What you expected to happen.
- What actually happened.
- Your browser and operating system.
- Any assistive technology you were using, if you choose to share it.

Providing screenshots or recordings is helpful but not required.

### Severity

Accessibility issues may be categorized during review.

#### Critical

Users cannot complete an important task.

Examples:

- A student cannot submit an outing request using a keyboard.
- A teacher cannot approve or reject requests with a screen reader.

#### High

Users can complete the task, but significant difficulty exists.

Examples:

- Form labels are not properly announced by assistive technologies.
- Request status information is difficult to access.

#### Medium

The issue reduces usability but does not block task completion.

Examples:

- Focus indicators are difficult to see.
- Navigation order is confusing in some sections.

#### Low

Minor accessibility improvements that have limited impact.

Examples:

- Non-essential images lack descriptive text.
- Heading structure could be improved.

Severity is assigned by project maintainers during issue review.

### How We Respond

When an accessibility issue is reported, we aim to:

- Acknowledge the report promptly.
- Review and investigate the issue.
- Provide updates when progress is made.
- Suggest temporary workarounds when available.
- Notify the reporter after a fix is released.
- Welcome feedback to confirm whether the issue has been resolved.

## Ownership and Maintenance

Accessibility is maintained by the Student Pass System project maintainers.

Responsibilities include:

- Reviewing accessibility-related issues.
- Evaluating new features for accessibility concerns.
- Updating accessibility documentation.
- Encouraging accessible development practices throughout the project.

Accessibility should be reviewed whenever major changes are made to the user interface or workflow.

## Supported Environments

The Student Pass System is designed for use on modern web browsers and devices.

### Browsers

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

### Devices

- Desktop computers
- Laptops
- Tablets
- Smartphones

### Input Methods

- Keyboard
- Mouse
- Touchscreen

### Assistive Technologies

The project aims to support:

- Screen readers
- Browser zoom functionality
- High-contrast display modes
- Keyboard-only navigation

Support may vary depending on browser and assistive technology combinations.

## Known Limitations

Accessibility testing is ongoing.

Areas currently under review include:

- Screen reader compatibility for future feature additions.
- Mobile accessibility across different device sizes.
- Accessibility behavior in third-party browser extensions or integrations.

Users are encouraged to report any barriers they encounter so improvements can be prioritized.

## Feedback and Improvements

We welcome suggestions for improving the accessibility of the Student Pass System and its development process.

For general accessibility suggestions, use the project's discussions or issue tracker.

If you experience a barrier that affects your ability to use the system, please report it through the accessibility issue process described above so we can investigate and improve the experience.
