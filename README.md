# Tailwind CSS Custom Styles Not Applied

This repository demonstrates a common issue in Tailwind CSS where custom styles or classes are not being applied due to problems with the `content` array in the `tailwind.config.js` file.

## Problem

Tailwind CSS requires you to specify the paths to the files containing your HTML, JavaScript (JSX/TSX), or other templates that use Tailwind classes. If these paths are incorrect, Tailwind won't detect the classes and the styles won't be applied.

## Solution

The solution involves correctly configuring the `content` array in your `tailwind.config.js` to include the paths to all relevant files.  Ensure you include every folder where you use Tailwind classes.