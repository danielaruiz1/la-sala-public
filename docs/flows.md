## User Flows (High-Level)

### 🔹 Visitor Flow

1. Lands on homepage → browses conversations.
2. Attempts to view premium content → prompted to register.
3. May subscribe to free notifications.

### 🔹 Registration & Login Flow

1. User signs up with email/password or OAuth.
2. Confirms account → redirected to profile.
3. Accesses free content → can upgrade to premium.

### 🔹 Subscription Flow

1. User selects a plan.
2. Stripe Checkout handles payment.
3. Webhook updates subscription status.
4. User gains access to premium content.

### 🔹 Admin Flow

1. Admin logs in.
2. Manages content (create/edit/delete).
3. Manages users (view, suspend).
4. Updates global configuration settings.
