import type { Config } from "tailwindcss";
import type { Config } from "tailwindcss";
export default {
export default {
  darkMode: ["class"],
  darkMode: ["class"],
  content: [
  content: [
    "./pages/**/*.{ts,tsx}",
    "./pages/**/*.{ts,tsx}",
    "./components/**/*.{ts,tsx}",
    "./components/**/*.{ts,tsx}",
    "./app/**/*.{ts,tsx}",
    "./app/**/*.{ts,tsx}",
    "./src/**/*.{ts,tsx}",
    "./src/**/*.{ts,tsx}",
  ],
  ],
  prefix: "",
  prefix: "",
  theme: {
  theme: {
    container: {
    container: {
      center: true,
      center: true,
      padding: 
'
2rem
'
,
      padding: 
"
2rem
"
,
      screens: {
      screens: {
        
'
2xl
'
: 
'
1400px
'
        
"
2xl
"
: 
"
1400px
",
      }
      }
,
    },
    },
    extend: {
    extend: {
      colors: {
      colors: {
        border: 
'
hsl(var(--border))
'
,
        border: 
"
hsl(var(--border))
"
,
        input: 
'
hsl(var(--input))
'
,
        input: 
"
hsl(var(--input))
"
,
        ring: 
'
hsl(var(--ring))
'
,
        ring: 
"
hsl(var(--ring))
"
,
        background: 
'
hsl(var(--background))
'
,
        background: 
"
hsl(var(--background))
"
,
        foreground: 
'
hsl(var(--foreground))
'
,
        foreground: 
"
hsl(var(--foreground))
"
,
        primary: {
        primary: {
          DEFAULT: 
'
hsl(var(--primary))
'
,
          DEFAULT: 
"
hsl(var(--primary))
"
,
          foreground: 
'
hsl(var(--primary-foreground))
'
          foreground: 
"
hsl(var(--primary-foreground))
",
        },
        },
        secondary: {
        secondary: {
          DEFAULT: 
'
hsl(var(--secondary))
'
,
          DEFAULT: 
"
hsl(var(--secondary))
"
,
          foreground: 
'
hsl(var(--secondary-foreground))
'
          foreground: 
"
hsl(var(--secondary-foreground))
",
        },
        },
        destructive: {
        destructive: {
          DEFAULT: 
'
hsl(var(--destructive))
'
,
          DEFAULT: 
"
hsl(var(--destructive))
"
,
          foreground: 
'
hsl(var(--destructive-foreground))
'
          foreground: 
"
hsl(var(--destructive-foreground))
",
        },
        },
        muted: {
        muted: {
          DEFAULT: 
'
hsl(var(--muted))
'
,
          DEFAULT: 
"
hsl(var(--muted))
"
,
          foreground: 
'
hsl(var(--muted-foreground))
'
          foreground: 
"
hsl(var(--muted-foreground))
",
        },
        },
        accent: {
        accent: {
          DEFAULT: 
'
hsl(var(--accent))
'
,
          DEFAULT: 
"
hsl(var(--accent))
"
,
          foreground: 
'
hsl(var(--accent-foreground))
'
          foreground: 
"
hsl(var(--accent-foreground))
",
        },
        },
        popover: {
        popover: {
          DEFAULT: 
'
hsl(var(--popover))
'
,
          DEFAULT: 
"
hsl(var(--popover))
"
,
          foreground: 
'
hsl(var(--popover-foreground))
'
          foreground: 
"
hsl(var(--popover-foreground))
",
        },
        },
        card: {
        card: {
          DEFAULT: 
'
hsl(var(--card))
'
,
          DEFAULT: 
"
hsl(var(--card))
"
,
          foreground: 
'
hsl(var(--card-foreground))
'
          foreground: 
"
hsl(var(--card-foreground))
",
        },
        },
      
sidebar: {
      
},
      
DEFAULT
: 
'hsl(var(--sidebar-background))',
      
keyframes
: 
{
        
foreground
: 
'hsl(var(--sidebar-foreground))',
        
"accordion-down"
: 
{
          
primary
: 
'hsl(var(--sidebar-primary))'
,
          
from
: 
{ height: "0" }
,
          
'primary-foreground'
: 
'hsl(
var(--
sidebar
-
primary
-
foreground
)
)'
,
          
to
: 
{ height: "
var(--
radix
-
accordion
-
content-height
)
" }
,
        
accent: 'hsl(var(--sidebar-accent))'
,
        
}
,
        
'accent
-
foreground'
: 
'hsl(var(--sidebar-accent-foreground))',
        
"accordion
-
up"
: 
{
          
border
: 
'hsl(
var(--
sidebar
-
border
)
)'
,
          
from
: 
{ height: "
var(--
radix
-
accordion-content-height
)
" }
,
          
ring
: 
'hsl(var(--sidebar-ring))'
          
to
: 
{ height: "0" },
        }
        }
,
        
},
        
float: {
          
borderRadius
: {
          
"0%, 100%"
: {
 transform: "translateY(0)" },
          
lg
: 
'var
(
--radius
)
'
,
          
"50%"
: 
{ transform: "translateY
(
-5px
)
" }
,
        
md: 'calc(var(--radius) - 2px)'
,
        
}
,
        
sm
: 
'calc(var(--radius) - 4px)'
        
shine
: 
{
          
},
          
"0%": { backgroundPosition: "200% 0" 
},
          
keyframes
: {
          
"100%"
: {
 backgroundPosition: "-200% 0" },
        
'accordion-down': {
        
},
      
from: {
      
},
      
height
: 
'0'
      
animation
: 
{
        
}
,
        
"accordion-down": "accordion-down 0.2s ease-out"
,
        
to
: 
{
        
"accordion-up"
: 
"accordion-up 0.2s ease-out",
        
height
: 
'var(--radix
-
accordion
-
content-height)'
        
float
: 
"float 3s ease
-
in
-
out infinite",
        
}
        
shine: "shine 8s ease-in-out infinite",
      },
      },
    
'accordion-up': {
    
},
  
from: {
  
},
  
height
: 
'var
(
--radix
-
accordion-content-height
)
'
  
plugins
: 
[require
(
"tailwindcss
-
animate"
)
],
					},
					to: {
						height: '0'
					}
				}
			},
			animation: {
				'accordion-down': 'accordion-down 0.2s ease-out',
				'accordion-up': 'accordion-up 0.2s ease-out'
			}
		}
	},
	plugins: [require("tailwindcss-animate")],
} satisfies Config;
} satisfies Config;
src/components/ToolCard.tsx
import { motion } from "framer-motion";
import { cn } from "@/lib/utils";
interface ToolCardProps {
  icon: React.ReactNode;
  title: string;
  description: string;
  onClick: () => void;
  className?: string;
}
export const ToolCard = ({ icon, title, description, onClick, className }: ToolCardProps) => {
  return (
    <motion.div
      whileHover={{ scale: 1.02 }}
      whileTap={{ scale: 0.98 }}
      className={cn(
        "group relative overflow-hidden rounded-xl bg-white p-6 shadow-md transition-all duration-300 hover:shadow-xl",
        className
      )}
      onClick={onClick}
    >
      <div className="mb-4 text-4xl text-gray-600 transition-transform duration-300 group-hover:scale-110">
        {icon}
      </div>
      <h3 className="mb-2 text-xl font-semibold text-gray-800">{title}</h3>
      <p className="text-sm text-gray-600">{description}</p>
      <div className="absolute inset-0 -z-10 bg-gradient-to-r from-transparent via-white/10 to-transparent opacity-0 transition-opacity duration-300 group-hover:opacity-100 animate-shine" />
    </motion.div>
  );
};
src/components/FileUploadZone.tsx
import { useState } from "react";
import { motion, AnimatePresence } from "framer-motion";
import { Upload } from "lucide-react";
interface FileUploadZoneProps {
  onFileSelect: (file: File) => void;
}
export const FileUploadZone = ({ onFileSelect }: FileUploadZoneProps) => {
  const [isDragging, setIsDragging] = useState(false);
  const handleDragOver = (e: React.DragEvent) => {
    e.preventDefault();
    setIsDragging(true);
  };
  const handleDragLeave = () => {
    setIsDragging(false);
  };
  const handleDrop = (e: React.DragEvent) => {
    e.preventDefault();
    setIsDragging(false);
    
    const files = Array.from(e.dataTransfer.files);
    if (files.length > 0 && files[0].type === "application/pdf") {
      onFileSelect(files[0]);
    }
  };
  const handleFileInput = (e: React.ChangeEvent<HTMLInputElement>) => {
    const files = e.target.files;
    if (files && files.length > 0) {
      onFileSelect(files[0]);
    }
  };
  return (
    <motion.div
      initial={false}
      animate={isDragging ? { scale: 1.02 } : { scale: 1 }}
      className="relative"
    >
      <input
        type="file"
        accept=".pdf"
        onChange={handleFileInput}
        className="absolute inset-0 cursor-pointer opacity-0"
      />
      <div
        onDragOver={handleDragOver}
        onDragLeave={handleDragLeave}
        onDrop={handleDrop}
        className={`flex min-h-[200px] flex-col items-center justify-center rounded-xl border-2 border-dashed p-8 transition-colors duration-300 ${
          isDragging
            ? "border-primary bg-primary/5"
            : "border-gray-200 hover:border-primary/50"
        }`}
      >
        <AnimatePresence mode="wait">
          <motion.div
            key={isDragging ? "dragging" : "idle"}
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            exit={{ opacity: 0, y: -20 }}
            className="text-center"
          >
            <Upload className="mx-auto mb-4 h-12 w-12 text-gray-400" />
            <h3 className="mb-2 text-lg font-medium text-gray-700">
              {isDragging ? "Drop your PDF here" : "Drag & Drop your PDF here"}
            </h3>
            <p className="text-sm text-gray-500">or click to browse</p>
          </motion.div>
        </AnimatePresence>
      </div>
    </motion.div>
  );
};
src/components/ProcessingAnimation.tsx
import { motion } from "framer-motion";
export const ProcessingAnimation = () => {
  return (
    <div className="flex flex-col items-center justify-center space-y-4">
      <motion.div
        className="h-16 w-16 rounded-full border-4 border-gray-200 border-t-primary"
        animate={{ rotate: 360 }}
        transition={{ duration: 1, repeat: Infinity, ease: "linear" }}
      />
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        className="text-lg font-medium text-gray-700"
      >
        Processing your PDF...
      </motion.p>
    </div>
  );
};
src/pages/Index.tsx
//
 
Update
 
this
 
page
 
(the
 
content is just a fallback if you fail to update the page)
import
 
{
 
useState
 
}
 
from
 
"react";
import { motion } from "framer-motion";
import {
  FileText,
  Scissors,
  Merge,
  Lock,
  Image,
  FileSignature,
  RotateCw,
  Type,
} from "lucide-react";
import { ToolCard } from "@/components/ToolCard";
import { FileUploadZone } from "@/components/FileUploadZone";
import { ProcessingAnimation } from "@/components/ProcessingAnimation";
import { useToast } from "@/components/ui/use-toast";
const tools = [
  {
    icon: <Scissors />,
    title: "Split PDF",
    description: "Separate one PDF into multiple files",
  },
  {
    icon: <Merge />,
    title: "Merge PDF",
    description: "Combine multiple PDFs into one",
  },
  {
    icon: <Lock />,
    title: "Protect PDF",
    description: "Encrypt your PDF with a password",
  },
  {
    icon: <Image />,
    title: "PDF to Image",
    description: "Convert PDF to JPG, PNG or TIFF",
  },
  {
    icon: <FileSignature />,
    title: "Sign PDF",
    description: "Add your signature to PDF",
  },
  {
    icon: <RotateCw />,
    title: "Rotate PDF",
    description: "Rotate your PDF pages easily",
  },
  {
    icon: <Type />,
    title: "OCR PDF",
    description: "Make your PDF searchable",
  },
  {
    icon: <FileText />,
    title: "Compress PDF",
    description: "Reduce PDF file size",
  },
];
const Index = () => {
const Index = () => {
  const [selectedTool, setSelectedTool] = useState<string | null>(null);
  const [isProcessing, setIsProcessing] = useState(false);
  const { toast } = useToast();
  const handleToolSelect = (title: string) => {
    setSelectedTool(title);
    toast({
      title: "Tool Selected",
      description: `${title} tool is ready to use`,
    });
  };
  const handleFileSelect = async (file: File) => {
    setIsProcessing(true);
    // Simulate processing
    await new Promise((resolve) => setTimeout(resolve, 2000));
    setIsProcessing(false);
    toast({
      title: "Success",
      description: "Your PDF has been processed successfully!",
    });
  };
  return (
  return (
    <div className="min-h-screen 
flex items
-
center
 
justify
-
center
 
bg
-
gray-100
">
    <div className="min-h-screen 
bg
-
gray-50
 
px
-
4
 
py
-
12
">
      <
div
 className="text-center">
      <
motion.
div
        
<h1 className
=
"text-4xl
 
font-bold
 
mb-4">Welcome
 
to
 
Your
 
Blank App</h1>
        
initial
=
{{
 
opacity:
 
0,
 
y:
 
20
 
}}
        
<p className
=
"text-xl
 
text-gray-600">Start
 
building
 
your
 
amazing
 
project here!</p>
        
animate
=
{{
 
opacity:
 
1,
 
y:
 
0
 
}}
        
</div>
        
className="mx-auto max-w-6xl"
      >
        <div className="mb-12 text-center">
          <motion.h1
            initial={{ opacity: 0, y: -20 }}
            animate={{ opacity: 1, y: 0 }}
            className="mb-4 text-4xl font-bold text-gray-900 sm:text-5xl"
          >
            Every PDF tool you need
          </motion.h1>
          <motion.p
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: 0.2 }}
            className="text-lg text-gray-600"
          >
            Easy, fast and secure PDF manipulation tools
          </motion.p>
        </div>
        {!selectedTool ? (
          <motion.div
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: 0.4 }}
            className="grid gap-6 sm:grid-cols-2 lg:grid-cols-4"
          >
            {tools.map((tool, index) => (
              <motion.div
                key={tool.title}
                initial={{ opacity: 0, y: 20 }}
                animate={{ opacity: 1, y: 0 }}
                transition={{ delay: index * 0.1 }}
              >
                <ToolCard
                  {...tool}
                  onClick={() => handleToolSelect(tool.title)}
                />
              </motion.div>
            ))}
          </motion.div>
        ) : (
          <motion.div
            initial={{ opacity: 0, scale: 0.95 }}
            animate={{ opacity: 1, scale: 1 }}
            className="mx-auto max-w-2xl"
          >
            <div className="mb-8">
              <button
                onClick={() => setSelectedTool(null)}
                className="text-sm text-gray-600 hover:text-gray-900"
              >
                ← Back to tools
              </button>
            </div>
            <div className="rounded-xl bg-white p-8 shadow-lg">
              <h2 className="mb-6 text-center text-2xl font-semibold text-gray-900">
                {selectedTool}
              </h2>
              {isProcessing ? (
                <ProcessingAnimation />
              ) : (
                <FileUploadZone onFileSelect={handleFileSelect} />
              )}
            </div>
          </motion.div>
        )}
      </motion.div>
    </div>
    </div>
  );
  );
};
};
Expand 2 lines ...			
package.json
Expand 44 lines ...			
    "cmdk": "^1.0.0",
    "cmdk": "^1.0.0",
    "date-fns": "^3.6.0",
    "date-fns": "^3.6.0",
    "embla-carousel-react": "^8.3.0",
    "embla-carousel-react": "^8.3.0",
    "framer-motion": "^11.17.0",
    "input-otp": "^1.2.4",
    "input-otp": "^1.2.4",
    "lucide-react": "^0.462.0",
    "lucide-react": "^0.462.0",
    "next-themes": "^0.3.0",
    "next-themes": "^0.3.0",
Expand 33 lines ...			
