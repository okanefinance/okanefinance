---
layout: page
title: Support
include_in_header: true
permalink: /support/
---

<style>
.support-hero {
    text-align: center;
    padding: 3rem 0;
    border-bottom: 1px solid #e6e6e6;
    margin-bottom: 3rem;
}

.support-hero h1 {
    font-size: 2.5rem;
    color: {{ site.feature_title_color | default: '#000000' }};
    margin-bottom: 1rem;
}

.support-hero p {
    font-size: 1.2rem;
    color: {{ site.feature_text_color | default: '#666666' }};
    max-width: 600px;
    margin: 0 auto;
}

.support-section {
    margin-bottom: 3rem;
}

.support-section h2 {
    font-size: 1.8rem;
    color: {{ site.feature_title_color | default: '#000000' }};
    margin-bottom: 1.5rem;
}

.contact-box {
    background: #f8f8f8;
    padding: 2rem;
    border-radius: 10px;
    text-align: center;
    margin-bottom: 3rem;
}

.contact-box h3 {
    color: {{ site.feature_title_color | default: '#000000' }};
    margin-bottom: 1rem;
}

.contact-email {
    font-size: 1.3rem;
    color: {{ site.link_color | default: '#1d63ea' }};
    text-decoration: none;
    font-weight: 500;
}

.contact-email:hover {
    text-decoration: underline;
}

.contact-description {
    margin-top: 1rem;
    color: {{ site.feature_text_color | default: '#666666' }};
    line-height: 1.6;
}

.faq-item {
    margin-bottom: 2rem;
    padding-bottom: 2rem;
    border-bottom: 1px solid #e6e6e6;
}

.faq-item:last-child {
    border-bottom: none;
}

.faq-question {
    font-size: 1.2rem;
    font-weight: 600;
    color: {{ site.feature_title_color | default: '#000000' }};
    margin-bottom: 0.8rem;
}

.faq-answer {
    color: {{ site.feature_text_color | default: '#666666' }};
    line-height: 1.6;
}

.app-info-section {
    background: #f8f8f8;
    padding: 2rem;
    border-radius: 10px;
    margin-top: 3rem;
}

.app-info-section h3 {
    color: {{ site.feature_title_color | default: '#000000' }};
    margin-bottom: 1rem;
}

.app-info-section p {
    color: {{ site.feature_text_color | default: '#666666' }};
    line-height: 1.6;
    margin-bottom: 0.5rem;
}

.footer-note {
    margin-top: 3rem;
    padding-top: 2rem;
    border-top: 1px solid #e6e6e6;
    text-align: center;
    font-size: 0.9rem;
    color: {{ site.footer_text_color | default: '#666666' }};
}

@media (max-width: 768px) {
    .support-hero h1 {
        font-size: 2rem;
    }

    .support-hero p {
        font-size: 1.1rem;
    }

    .contact-email {
        font-size: 1.1rem;
    }
}
</style>

<div class="support-hero">
    <h1>Okane Budgeting Support</h1>
    <p>Get help with setup, troubleshooting, and questions about Okane Budgeting.</p>
</div>

<div class="support-section">
    <h2>Contact Support</h2>
    <div class="contact-box">
        <h3>Need Help?</h3>
        <a href="mailto:mike.from.okane@gmail.com" class="contact-email">mike.from.okane@gmail.com</a>
        <p class="contact-description">
            Contact us for help with account setup, syncing issues, technical questions, or bug reports.
            We typically respond within 24-48 hours.
        </p>
    </div>
</div>

<div class="support-section">
    <h2>Frequently Asked Questions</h2>

    <div class="faq-item">
        <div class="faq-question">How do I connect my spreadsheet?</div>
        <div class="faq-answer">
            When you first open Okane Budgeting, you'll be prompted to either create a new budget spreadsheet or connect an existing one.
            Simply sign in with your Google account and grant the necessary permissions to access Google Sheets.
            The app will guide you through selecting or creating your budget spreadsheet.
            If you encounter any issues, make sure you're signed in with the correct Google account that has access to your spreadsheet.
        </div>
    </div>

    <div class="faq-item">
        <div class="faq-question">What should I do if my budget data is not syncing?</div>
        <div class="faq-answer">
            If your budget data isn't syncing properly, try these steps:
            First, check your internet connection. Then, pull down to refresh the data in the app.
            If the issue persists, go to Settings and verify that you're connected to the correct spreadsheet.
            You may need to sign out and sign back in to refresh your Google account permissions.
            If you continue to experience issues, please contact support with details about when the syncing stopped working.
        </div>
    </div>

    <div class="faq-item">
        <div class="faq-question">How do I report a bug?</div>
        <div class="faq-answer">
            To report a bug, please email us at mike.from.okane@gmail.com with the following information:
            A description of the issue you're experiencing, the steps to reproduce the problem,
            your device model and iOS version, and if possible, screenshots showing the issue.
            The more details you provide, the faster we can identify and fix the problem.
        </div>
    </div>

    <div class="faq-item">
        <div class="faq-question">How do I request a feature?</div>
        <div class="faq-answer">
            We love hearing from our users! To request a new feature, send us an email at mike.from.okane@gmail.com
            with "Feature Request" in the subject line. Describe the feature you'd like to see and how it would
            help improve your budgeting experience. We carefully review all suggestions and prioritize features
            based on user feedback and development resources.
        </div>
    </div>

    <div class="faq-item">
        <div class="faq-question">Is my financial data private?</div>
        <div class="faq-answer">
            Yes, your privacy and data security are our top priorities. Okane Budgeting stores all your financial
            data in your own Google Sheets spreadsheet, which remains in your Google Drive under your control.
            We do not store, copy, or have access to your financial data on our servers. The app only accesses
            your spreadsheet data when you're actively using it, and all communication with Google's servers
            is encrypted. For more details, please review our Privacy Policy.
        </div>
    </div>
</div>

<div class="app-info-section">
    <h3>About Okane Budgeting</h3>
    <p><strong>App Name:</strong> Okane Budgeting</p>
    <p><strong>Developer:</strong> Okane Software LLC</p>
    <p>
        Okane Budgeting is a spreadsheet-connected budgeting app designed to help you manage your money
        with flexibility and clarity. By leveraging the power of Google Sheets, you maintain full control
        over your financial data while enjoying a beautiful, intuitive mobile interface for tracking expenses
        and monitoring your budget on the go.
    </p>
</div>

<div class="footer-note">
    <p>For App Store review or urgent support issues, please contact us at mike.from.okane@gmail.com</p>
</div>