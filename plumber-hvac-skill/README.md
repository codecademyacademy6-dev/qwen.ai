# Plumber HVAC Contractor Comms Kit - Claude Skill

A comprehensive communication toolkit for plumbing and HVAC contractors, designed to streamline customer interactions, estimates, follow-ups, and service communications.

## Overview

This Claude Skill provides ready-to-use templates and prompts for:
- Customer service calls and responses
- Estimate and quote generation
- Appointment scheduling and reminders
- Follow-up communications
- Emergency service responses
- Maintenance plan proposals
- Invoice and payment communications
- Review and referral requests

## Structure

```
plumber-hvac-skill/
├── README.md                 # This file
├── prompts/                  # Main prompt templates
│   ├── initial-contact.md    # First customer interaction
│   ├── estimate-request.md   # Quote generation
│   ├── appointment-confirm.md # Scheduling confirmations
│   ├── follow-up.md          # Post-service follow-ups
│   ├── emergency-response.md # Urgent service calls
│   ├── maintenance-plan.md   # Service plan proposals
│   ├── invoice-reminder.md   # Payment communications
│   └── review-request.md     # Customer feedback requests
├── templates/                # Fill-in-the-blank templates
│   ├── phone-script.txt      # Phone call scripts
│   ├── email-templates.txt   # Email formats
│   └── sms-templates.txt     # Text message formats
└── resources/                # Additional resources
    ├── common-issues.md      # FAQ and troubleshooting guide
    └── pricing-guide.md      # Sample pricing structures
```

## Quick Start

1. **Browse the prompts** in the `prompts/` directory for specific communication scenarios
2. **Copy the relevant template** and customize with your business details
3. **Use with Claude** by pasting the prompt and providing customer-specific details

## Usage Examples

### Generate an Estimate Response
```
Use: prompts/estimate-request.md
Provide: Customer name, issue description, property type
Output: Professional estimate email with pricing breakdown
```

### Handle Emergency Call
```
Use: prompts/emergency-response.md
Provide: Issue type, urgency level, availability
Output: Immediate response script with next steps
```

### Schedule Appointment Confirmation
```
Use: prompts/appointment-confirm.md
Provide: Customer info, date/time, service type, technician name
Output: Confirmation message with preparation instructions
```

## Customization

Replace the following placeholders throughout all templates:
- `[COMPANY_NAME]` - Your business name
- `[PHONE_NUMBER]` - Your contact number
- `[EMAIL_ADDRESS]` - Your email address
- `[WEBSITE]` - Your website URL
- `[SERVICE_AREA]` - Areas you serve
- `[LICENSE_NUMBER]` - Your contractor license

## Best Practices

1. **Personalize** each communication with the customer's name and specific situation
2. **Respond promptly** - aim for within 1 hour during business hours
3. **Be clear about pricing** - provide ranges or estimates upfront when possible
4. **Set expectations** - communicate arrival windows and potential delays
5. **Follow up** - check in after service completion
6. **Request reviews** - ask satisfied customers for feedback

## License

This toolkit is provided as-is for use by plumbing and HVAC contractors. Feel free to modify and adapt for your specific business needs.

## Support

For questions or suggestions for additional templates, please contribute to this repository or contact your system administrator.
