# Simple Tailwind CSS Starter

This is an extremley simple setup to develop Tailwind projects. This will be used in my Tailwind From Scratch course.

## Usage

Install dependencies

```
npm install
```

Run Tailwind CLI in watch mode

```
npm run dev
```

You can use tailwind classes in any .html files in the root directory

Put any custom CSS that you may have in the **src/input.css** file

Add any config values to the **tailwind.config.js** file

To build once, run

```
npm run build
```

You only need to deploy your html files and css/style.css

Section container: max-w-6xl mx-auto text-center px-10;

Section content:  max-w-3xl mx-auto mb-16 text-xl leading-9 text-center text-darkGrayishBlue;

Button container: flex flex-col justify-center w-full space-y-6 
text-xl text-white md:flex-row md:space-y-0 md:space-x-4;

h3: mb-8 text-4xl font-bold text-darkGrayishBlue md:text-5xl;