# Rownd

## Redefining Authentication for Modern Applications

Rownd is a contextual authentication platform that simplifies user authentication while enhancing security and user experience across web and mobile applications. Our VISUAL SDK and customizable components enable developers to implement secure, passwordless authentication in minutes rather than weeks.

## Why Choose Rownd?

- **Passwordless Authentication**: Deliver frictionless, secure sign-in experiences with social sign in, Google, Apple, passkeys and magic links
- **VISUAL SDK**: Implement and customize authentication UI without complex coding
- **Enterprise-Grade Security**: SOC2 certified with advanced encryption and compliance with global standards
- **Cross-Platform Support**: Comprehensive suite of SDKs for any platform or framework
- **Quick Implementation**: Add authentication to your application in minutes, not days
- **Proven Reliability**: Trusted by product-led teams for scalable authentication solutions

## Key Platform Features

### Automations

Automations are no-code tools that empower you to enhance and optimize your app's sign-up process without writing a single line of code. Configure automations to:

- **Sign-In Prompts**: Trigger authentication prompts based on clicks, time duration, sessions, or page visits
- **User Data Collection**: Easily gather additional user information as needed
- **Sign-Out Events**: Enable users to end their sessions through any element you choose
- **Promotional Opt-ins**: Request marketing consent with customizable messaging
- **Passkey Integration**: Prompt users to add passkeys to their accounts for enhanced security

All automations can be customized and deployed instantly without requiring app updates, making it perfect for rapid iteration and A/B testing of authentication flows.

### User Groups & Permissions

Manage user access and capabilities with Rownd's flexible grouping system:

- **Role-Based Access**: Easily assign users to specific groups with predefined permissions

- **Dynamic Group Assignment**: Automatically add users to groups based on their actions or attributes
- **Administrative Tools**: Manage group memberships through the dashboard or API

### Design Customization

Rownd offers extensive customization options to ensure authentication UIs match your brand perfectly:

- **Global Styling**: Customize colors, logos, corner radii, and mode (light/dark) across all Rownd components
- **Pre-built UI Components**: Every authentication interface is fully customizable while maintaining security best practices
- **No-code Customization**: Make changes through the dashboard without deploying code updates

#### Customizable UI Elements

- **Sign-in Modal**: Change the appearance of authentication options and screens
- **Profile Management**: Tailor user profile interfaces to match your product's look and feel
- **Verification Emails**: Customize email templates with your branding and messaging
- **Mobile Experiences**: Optimize authentication for mobile web and native apps

#### Visual Styling Options

Customize virtually every aspect of the authentication experience:

- **Appearance**: Sync with user OS settings or force light/dark mode
- **Primary Color**: Match your brand colors in both light and dark modes
- **Visual Elements**: Toggle visual flourishes, illustrations, and decorative elements
- **Corner Radius**: Choose between rounded and square corners for UI components
- **Custom Logos**: Add your logo to sign-in modals, with separate versions for light/dark modes
- **Background Effects**: Enable or disable overlay blurring for modals

Apply your changes instantly across all platforms without requiring app updates, making it perfect for A/B testing different authentication experiences.

## Open Source SDKs

Rownd provides a comprehensive suite of open-source SDKs for any platform or framework:

### Frontend SDKs
| Platform | Description |
|----------|-------------|
| [React](https://github.com/rownd/react) | React bindings for web applications |
| [Angular](https://github.com/rownd/angular) | SDK for Angular Single Page Apps |
| [Vue](https://github.com/rownd/vue) | Rownd bindings for Vue.js applications |

### Server SDKs
| Platform | Description |
|----------|-------------|
| [Node.js](https://github.com/rownd/node) | Server-side integration for Node.js |
| [Django](https://github.com/rownd/django) | Python Django framework integration |
| [WordPress](https://github.com/rownd/wordpress) | WordPress plugin for easy integration |
| [Ruby on Rails](https://github.com/rownd/devise-rownd) | Devise integration for Ruby on Rails |
| [Go](https://github.com/rownd/client-go) | Rownd client SDK for Go |
| [.NET](https://github.com/rownd/dotnet) | .NET Core bindings for server-side integration |

### Mobile App SDKs
| Platform | Description |
|----------|-------------|
| [React Native](https://github.com/rownd/react-native) | SDK for mobile apps built in React Native |
| [iOS](https://github.com/rownd/ios) | Native SDK for iOS applications |
| [Android](https://github.com/rownd/android) | Native SDK for Android applications |
| [Flutter](https://github.com/rownd/flutter) | Rownd bindings for Flutter mobile apps |
| [.NET MAUI](https://github.com/rownd/dotnet-maui) | Rownd bindings for .NET MAUI |
| [Xamarin](https://github.com/rownd/xamarin) | Rownd bindings for Xamarin |
| [Unity](https://github.com/rownd/unity) | SDK for Unity game development |

## SDK Highlights

### React SDK Packages
The React SDK includes three specialized packages to support various React frameworks:
- **[react](https://github.com/rownd/react/tree/main/packages/react)**: Core React integration
- **[next](https://github.com/rownd/react/tree/main/packages/next)**: Optimized for Next.js applications
- **[remix](https://github.com/rownd/react/tree/main/packages/remix)**: Tailored for Remix framework

## Key Features

- **Passwordless Authentication**: Secure sign-in via magic links, passkeys, and social authentication
- **Pre-built UI Components**: Customizable authentication interfaces that work across devices
- **User Data Management**: Secure storage and management of user profile information
- **Real-time Metrics**: Actionable insights for optimizing sign-in flows and user retention
- **Adaptive Sign-in**: Server-side updates to adjust sign-in methods based on user behavior
- **Enterprise Security**: SOC2 certified with advanced encryption and compliance standards
- **Migration Tools**: Easy transitions from Firebase, Auth0, and AWS Cognito authentication systems

## Integration Benefits

- **Increased Conversion Rates**: Boost sign-up and retention with frictionless authentication
- **Reduced Development Time**: Implement authentication in minutes instead of weeks
- **Enhanced User Experience**: Deliver seamless, consistent authentication across all platforms
- **Regulatory Compliance**: Meet global privacy and security requirements effortlessly
- **Customizable Branding**: Match your authentication experience to your brand identity
- **Scalable Infrastructure**: Handle growth from startups to enterprise with reliable performance

## Getting Started

1. Visit [docs.rownd.io](https://docs.rownd.io) for comprehensive documentation
2. Sign up for a free account at [rownd.com](https://app.rownd.io)
3. Choose the SDK for your platform and follow the integration guide
4. Customize your authentication experience

## Setting Up Your Account

### Creating Your Rownd Application

1. **Sign up for an account**: Visit [rownd.com](https://app.rownd.io) and click "Try now" or "Sign in" to create your account
2. **Create a new application**: From your dashboard, select "Create new application" and provide a name and description
3. **Configure your application**: Set up your authentication methods (passkeys, smart links, social logins) in the Sign-in methods section. 

### Getting Your App Keys

1. **Access your application dashboard**: Select your application from the Rownd dashboard
2. **Navigate to API Keys**: Find the "API Keys" section.
3. **Copy your app key**: Your application key will look like `key_d7d4chwlj5q4i43435zrg1pa2s`
4. **Copy your app secret**: Your application secret will look like `ras_8f7h2j3k4l5m6n238r9s0t123523asdv3w4x5y6z7` and should only be used server-side
5. **Store securely**: Keep your app key and secret secure as they control access to your Rownd application

### Implementing Rownd in Your Application

#### Client-side Implementation
For a React application:

```jsx
import { RowndProvider } from '@rownd/react';

function App() {
  return (
    <RowndProvider appKey="your_app_key_here">
      <YourApplication />
    </RowndProvider>
  );
}
```

#### Server-side Implementation
For a Node.js backend:

```javascript
import { Rownd } from '@rownd/node';

const rownd = new Rownd({
  appKey: 'your_app_key_here',
  appSecret: 'your_app_secret_here'
});

// Verify a user's authentication token
const verifyToken = async (req, res, next) => {
  try {
    const token = req.headers.authorization?.split(' ')[1];
    const verifiedUser = await rownd.auth.verifyToken(token);
    req.user = verifiedUser;
    next();
  } catch (error) {
    res.status(401).json({ error: 'Unauthorized' });
  }
};
```

For other platforms, refer to the specific SDK documentation to integrate your app key and secret properly.

## Resources

- [Official Documentation](https://docs.rownd.io)
- [Rownd Website](https://rownd.com)
- [Blog](https://rownd.com/blog)
- [Support](mailto:support@rownd.io)

## Security

Rownd is SOC2 certified and designed with security as a priority. We implement industry best practices including:

- Advanced encryption for data at rest and in transit
- Compliance with global security standards
- Regular security audits and penetration testing
- Secure authentication methods like passkeys and magic links

## Community and Support

- Email: [support@rownd.io](mailto:support@rownd.io)
- Twitter: [@RowndHQ](https://twitter.com/RowndHQ)
- LinkedIn: [company/rownd](https://www.linkedin.com/company/rownd)

## License

All Rownd SDKs are available under open source licenses. See individual repositories for specific license details.