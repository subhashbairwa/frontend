<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Management System</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">
    <div class="max-w-4xl mx-auto p-6">
        <h1 class="text-3xl font-bold text-center mb-6">Employee Management System</h1>
        
        <section class="mb-6">
            <h2 class="text-2xl font-semibold">Overview</h2>
            <p class="mt-2 text-gray-700">The Employee Management System is a web-based application designed to streamline task management within an organization. The system ensures secure login access for admins and authorized users while enabling efficient task assignment and tracking for employees.</p>
        </section>
        
        <section class="mb-6">
            <h2 class="text-2xl font-semibold">Features</h2>
            
            <div class="mt-4 p-4 bg-white rounded-lg shadow-md">
                <h3 class="text-xl font-semibold">1. Authentication & Authorization</h3>
                <ul class="list-disc list-inside text-gray-700 mt-2">
                    <li>Only admins and authorized users can log in.</li>
                    <li>Secure authentication mechanism for user verification.</li>
                </ul>
            </div>
            
            <div class="mt-4 p-4 bg-white rounded-lg shadow-md">
                <h3 class="text-xl font-semibold">2. Admin Panel</h3>
                <ul class="list-disc list-inside text-gray-700 mt-2">
                    <li>Admin can create tasks for employees.</li>
                    <li>Admin has full control over task management.</li>
                </ul>
            </div>
            
            <div class="mt-4 p-4 bg-white rounded-lg shadow-md">
                <h3 class="text-xl font-semibold">3. Employee Dashboard</h3>
                <ul class="list-disc list-inside text-gray-700 mt-2">
                    <li>Employees can accept assigned tasks.</li>
                    <li>Employees can track task status, categorized as:</li>
                    <ul class="list-disc list-inside ml-4 text-gray-600">
                        <li>New Tasks</li>
                        <li>Accepted Tasks</li>
                        <li>Completed Tasks</li>
                        <li>Failed Tasks</li>
                    </ul>
                    <li>Employees have full access to task descriptions and details.</li>
                </ul>
            </div>
        </section>
    </div>
</body>
</html>
