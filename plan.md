# HTML Styling Plan for DS Unit 2 Sprint 8 with Tailwind CSS

## Overview

This document outlines a plan for styling all HTML files in the course content, following the order specified in the manifest.xml file. The styling will be applied in batches of 5 files, with each file receiving consistent styling and navigation links to move forward and backward through the lesson content. We will implement the styling using Tailwind CSS according to the provided style guide.

## Styling Approach

### Tailwind CSS Implementation

1. **Setup**:
   - Add Tailwind CSS via CDN for quick implementation
   - Use the Play CDN for development: `<script src="https://cdn.tailwindcss.com"></script>`
   - Configure Tailwind with custom colors to match the style guide

2. **Custom Configuration**:
   ```html
   <script>
     tailwind.config = {
       theme: {
         extend: {
           colors: {
             primary: '#93005a',
             secondary: '#00808c',
             background: '#f5f5f5',
             textColor: '#333',
           },
           maxWidth: {
             'content': '1200px',
           },
         }
       }
     }
   </script>
   ```

### Global Styling Elements

1. **Typography**: Use Arial, sans-serif as specified in the style guide
2. **Color Scheme**: Implement the specified color scheme:
   - Primary: #93005a
   - Secondary: #00808c
   - Background: #f5f5f5
   - Text: #333
   - Links: #333 (normal), white (hover)
3. **Layout**: Create a responsive layout with:
   - Max-width of 1200px
   - Proper spacing and margins
   - Content sections with white background and subtle shadow

### Navigation System

1. **Navigation Controls**:
   - "Previous" button to navigate to the previous page in the sequence
   - "Next" button to navigate to the next page in the sequence
   - "Back to Sprint Content" link as specified in the style guide
   - "Unit Videos" link as specified in the style guide
   - Hover effects with color transition

2. **Navigation Logic**:
   - Use the manifest.xml structure to determine the correct sequence
   - Handle special cases for first and last pages in modules
   - Provide clear module/section indicators

## Implementation Plan by Batches

### Batch 1:

1. `how-to-pass-this-sprint.html`
2. `live-class-offerings.html`
3. `career-coaching.html`
4. `github-profile-checklist.html`
5. `academic-support.html`

**Implementation Tasks:**
- Set up Tailwind CSS via CDN
- Create base HTML structure with Tailwind classes
- Implement header and footer templates
- Add navigation controls based on manifest order
- Test responsive design

### Batch 2:

1. `what-is-codesignal-and-how-to-create-your-account.html`
2. `codesignal-user-interface-overview.html`
3. `codesignal-arcade.html`
4. `introduction-to-gca.html`
5. `additional-information-on-gca.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from Batch 1
- Ensure navigation links connect properly

### Batch 3:

1. `understand-the-problem-solving-framework.html`
2. `module-1-guided-project.html` (if exists, or next in sequence)
3. `module-1-practice.html`
4. `module-1-check-for-understanding.html` (if exists, or next in sequence)
5. `module-1-take-practice-gca-test.html` (if exists, or next in sequence)

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 4:

1. `solve-a-problem-based-on-if-a-string-is-determined-to-be-a-palindrome.html`
2. `module-2-guided-project.html`
3. `module-2-practice.html`
4. `module-2-check-for-understanding.html` (if exists, or next in sequence)
5. `module-2-take-practice-gca-test.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 5:

1. `define-2d-arrays-and-how-to-access-elements-within-them.html`
2. `apply-moving-window-techniques-to-arrays.html`
3. `module-3-guided-project.html`
4. `module-3-practice.html`
5. `module-3-practice-1.html` (if exists, or next in sequence)

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 6:

1. `module-3-practice-2.html` (if exists, or next in sequence)
2. `module-3-check-for-understanding.html` (if exists, or next in sequence)
3. `module-3-take-practice-gca-test.html`
4. `module-4-guided-project.html`
5. `module-4-practice-1.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 7:

1. `building-your-github.html`
2. `getting-started-with-github.html`
3. `creating-your-profile-readme.html`
4. `pinning-projects.html`
5. `creating-effective-content-for-your-resume-2.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 8:

1. `adding-skills.html`
2. `adding-projects.html`
3. `experience-pre-bloomtech.html`
4. `finding-jobs.html`
5. `example-job-titles-based-on-your-skills-so-far.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 9:

1. `where-to-look-for-roles-2.html`
2. `learn-how-to-setup-and-build-your-github-profile.html`
3. `learn-how-to-create-and-add-relevant-contributions-to-your-github-profile.html`
4. `module-4-practice-2.html`
5. `module-4-take-practice-gca-test.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 10:

1. `prepare-for-code-along-2d-arrays-and-moving-windows.html`
2. `attend-get-it-done.html`
3. `prepare-for-code-along-2.html`
4. `next-step.html`
5. `welcome.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 11:

1. `practice-2.html`
2. `practice-2-copy.html`
3. `practice-3.html`
4. `practice-4.html`
5. `understand-objects-and-letter-counts.html`
6. `review-of-basic-coding-knowledge-functions-variables-and-math.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly

### Batch 12

1. `tech-requirements.html`
2. `unit-overview.html`
3. `utilize-boolean-programming-logic-and-if-statements.html`
4. `write-an-effective-cold-outreach-message.html`
5. `write-code-that-processes-and-uses-multidimensional-arrays.html`
6. `engagement-expectations.html`

**Implementation Tasks:**
- Apply consistent styling with Tailwind from previous batches
- Ensure navigation links connect properly
- Final testing of all navigation links

## Technical Implementation Details

### HTML Structure with Tailwind CSS

For each HTML file, the following structure will be implemented:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title - DS Unit 2 Sprint 8</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            colors: {
              primary: '#93005a',
              secondary: '#00808c',
              background: '#f5f5f5',
              textColor: '#333',
            },
            maxWidth: {
              'content': '1200px',
            },
          }
        }
      }
    </script>
    <style type="text/tailwindcss">
      @layer utilities {
        .content-section {
          @apply bg-white p-8 mb-8 rounded-lg shadow-md;
        }
        .nav-link {
          @apply text-textColor no-underline px-5 py-2.5 rounded-md bg-white transition-colors duration-300 hover:bg-primary hover:text-white;
        }
        .video-container {
          @apply relative pb-[56.25%] h-0 overflow-hidden max-w-full my-5;
        }
        .video-container iframe {
          @apply absolute top-0 left-0 w-full h-full;
        }
      }
    </style>
</head>
<body class="font-[Arial,sans-serif] max-w-content mx-auto p-5 bg-background text-textColor leading-relaxed">
    <div class="flex gap-5 mb-8">
        <a href="../DS-S8-content.html" class="nav-link">← Back to Sprint Content</a>
        <a href="../DS-Unit-2-videos.html" class="nav-link">Unit Videos</a>
    </div>

    <header class="mb-8">
        <h1 class="text-3xl font-bold text-primary mb-2">DS Unit 2 Sprint 8</h1>
        <h2 class="text-2xl font-semibold text-secondary">Page Title</h2>
    </header>

    <main class="content-section">
        <!-- Original content goes here -->
    </main>

    <footer class="mt-10">
        <nav class="flex justify-between">
            <a href="previous-page.html" class="nav-link">← Previous: Previous Page Title</a>
            <a href="next-page.html" class="nav-link">Next: Next Page Title →</a>
        </nav>
    </footer>

    <!-- Tab System JavaScript (if needed) -->
    <script>
      function openTab(evt, tabName) {
          var i, tabcontent, tabbuttons;

          tabcontent = document.getElementsByClassName("tab-content");
          for (i = 0; i < tabcontent.length; i++) {
              tabcontent[i].style.display = "none";
          }

          tabbuttons = document.getElementsByClassName("tab-button");
          for (i = 0; i < tabbuttons.length; i++) {
              tabbuttons[i].className = tabbuttons[i].className.replace(" active", "");
          }

          document.getElementById(tabName).style.display = "block";
          evt.currentTarget.className += " active";
      }
    </script>
</body>
</html>
```

### Tab System with Tailwind (When Needed)

For pages requiring tab functionality:

```html
<div class="mb-5">
    <div class="flex gap-2.5 border-b-2 border-gray-200">
        <button class="tab-button active px-4 py-2 bg-white hover:bg-primary hover:text-white transition-colors duration-300" onclick="openTab(event, 'tab1')">Tab 1</button>
        <button class="tab-button px-4 py-2 bg-white hover:bg-primary hover:text-white transition-colors duration-300" onclick="openTab(event, 'tab2')">Tab 2</button>
    </div>

    <div id="tab1" class="tab-content block p-4">
        <!-- Tab 1 content -->
    </div>

    <div id="tab2" class="tab-content hidden p-4">
        <!-- Tab 2 content -->
    </div>
</div>
```

### Video Container with Tailwind

For embedding videos:

```html
<div class="video-container">
    <iframe src="https://fast.wistia.net/embed/iframe/VIDEO_ID" allowtransparency="true" frameborder="0" scrolling="no" class="wistia_embed" name="wistia_embed" allowfullscreen mozallowfullscreen webkitallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>
```

## Testing Plan

For each batch:

1. Test all HTML files in desktop and mobile viewports
2. Verify all navigation links work correctly
3. Check for any styling inconsistencies
4. Validate HTML

## Quality Checklist

For each batch, ensure:
- [ ] Responsive design works on all screen sizes
- [ ] All videos are properly embedded
- [ ] Navigation links are working
- [ ] Tabs function correctly (where applicable)
- [ ] Styles are consistent across all pages
- [ ] JavaScript functions are properly scoped
- [ ] All interactive elements have hover states
- [ ] Content is properly formatted and readable
- [ ] Videos are responsive and maintain aspect ratio

## Conclusion

This plan provides a structured approach to styling all HTML files in the course content using Tailwind CSS. By working in batches of 5 files, the styling can be applied consistently and methodically, ensuring a cohesive learning experience for students following the course. The implementation follows the style guide requirements while leveraging the utility-first approach of Tailwind CSS for efficient styling.