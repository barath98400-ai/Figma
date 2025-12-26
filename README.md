# Ex09 Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
UI PAGE:
import { Button } from "./ui/button";
import { Card, CardContent } from "./ui/card";
import { Calendar, MapPin, User } from "lucide-react";

interface HomePageProps {
  onNavigate: (page: string) => void;
}

export function HomePage({ onNavigate }: HomePageProps) {
  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100">
      {/* Navigation */}
      <nav className="bg-white shadow-md">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex justify-between items-center h-16">
            <h1 className="text-indigo-600">Event Management System</h1>
            <div className="flex gap-6">
              <button
                onClick={() => onNavigate("home")}
                className="text-gray-700 hover:text-indigo-600 transition-colors"
              >
                Home
              </button>
              <button
                onClick={() => onNavigate("events")}
                className="text-gray-700 hover:text-indigo-600 transition-colors"
              >
                Events
              </button>
              <button
                onClick={() => onNavigate("register")}
                className="text-gray-700 hover:text-indigo-600 transition-colors"
              >
                Register
              </button>
            </div>
          </div>
        </div>
      </nav>

      {/* Hero Section */}
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div className="text-center mb-12">
          <h2 className="text-indigo-600 mb-4">Welcome to CodeFest 2026</h2>
          <p className="text-gray-600 max-w-2xl mx-auto">
            Join us for an exciting coding competition and tech event at Saveetha Engineering College, Chennai
          </p>
        </div>

        {/* Event Banner */}
        <Card className="mb-12 overflow-hidden bg-gradient-to-r from-indigo-500 to-purple-600 text-white">
          <CardContent className="p-8">
            <div className="grid md:grid-cols-2 gap-8">
              <div>
                <h3 className="mb-4 text-white">CodeFest 2026</h3>
                <div className="space-y-3">
                  <div className="flex items-center gap-3">
                    <Calendar className="w-5 h-5" />
                    <span>January 11, 2026</span>
                  </div>
                  <div className="flex items-center gap-3">
                    <MapPin className="w-5 h-5" />
                    <span>Majestorium Hall, Saveetha Engineering College, Chennai</span>
                  </div>
                  <div className="flex items-center gap-3">
                    <User className="w-5 h-5" />
                    <span>Coordinator: Jeevanantham C</span>
                  </div>
                </div>
              </div>
              <div className="flex flex-col justify-center gap-4">
                <p className="text-white/90">
                  Experience a day filled with coding challenges, networking opportunities, and technical workshops. Don't miss this opportunity to showcase your skills!
                </p>
                <div className="flex gap-4">
                  <Button
                    onClick={() => onNavigate("events")}
                    variant="secondary"
                    size="lg"
                  >
                    View Events
                  </Button>
                  <Button
                    onClick={() => onNavigate("register")}
                    variant="outline"
                    size="lg"
                    className="bg-white text-indigo-600 hover:bg-gray-100"
                  >
                    Register Now
                  </Button>
                </div>
              </div>
            </div>
          </CardContent>
        </Card>

        {/* Features */}
        <div className="grid md:grid-cols-3 gap-6">
          <Card>
            <CardContent className="p-6">
              <div className="text-indigo-600 mb-3"></div>
              <h4 className="mb-2">Competitions</h4>
              <p className="text-gray-600">
                Participate in exciting coding competitions and win amazing prizes
              </p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6">
              <div className="text-indigo-600 mb-3"></div>
              <h4 className="mb-2">Workshops</h4>
              <p className="text-gray-600">
                Learn from industry experts through hands-on technical workshops
              </p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6">
              <div className="text-indigo-600 mb-3"></div>
              <h4 className="mb-2">Networking</h4>
              <p className="text-gray-600">
                Connect with fellow developers and build lasting professional relationships
              </p>
            </CardContent>
          </Card>
        </div>
      </div>
    </div>
  );
}
```
# OUTPUT:
<img width="1905" height="859" alt="529478903-ee15144a-285d-489e-b99a-91f6d5edae68" src="https://github.com/user-attachments/assets/7ee90554-0cb3-4799-95d3-0b0131f52123" />
<img width="1900" height="847" alt="529478958-782c7ed1-a679-4a3e-aca5-084cbde4efbb" src="https://github.com/user-attachments/assets/1afa8a42-d32e-4119-9a7a-eb203bba4b29" />
<img width="1896" height="847" alt="529479225-e89dde59-b916-4b5e-99de-e7cac6d1c02e" src="https://github.com/user-attachments/assets/f544fc13-d9ed-4a06-84a4-222167c6be91" />

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
