# Ex08 Event Registration Web Application
## Date:20-03-2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
PAGE 1
import freeFlatColorPhysicalBackgroundImagesFlatSportsH5BackgroundPhotoBackgroundPngAndVectors1 from "./free-flat-color-physical-background-images-flat-sports-h5-background-photo-background-PNG-and-vectors-1.png";
import rectangle1 from "./rectangle-1.svg";

export const Iphone = (): JSX.Element => {
  return (
    <div className="bg-white w-full min-w-[393px] min-h-[852px] relative">
      <img
        className="absolute top-0 left-0 w-[393px] h-[852px] aspect-[0.56] object-cover"
        alt="Free flat color"
        src={
          freeFlatColorPhysicalBackgroundImagesFlatSportsH5BackgroundPhotoBackgroundPngAndVectors1
        }
      />

      <img
        className="top-[385px] h-[57px] absolute left-[57px] w-[273px]"
        alt="Rectangle"
        src={rectangle1}
      />

      <div className="absolute top-[402px] left-[140px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        REGISTER
      </div>

      <div className="top-[464px] h-[61px] bg-[#ff0000] absolute left-[57px] w-[273px]" />

      <div className="absolute top-[129px] left-[87px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        SPORTS DAY EVENTS
      </div>

      <div className="absolute top-[480px] left-[140px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        SIGN IN
      </div>
    </div>
  );
};

PAGE 2
import { ArrowRight } from "./ArrowRight";
import figma21 from "./figma-2-1.png";

const events = [
  {
    label: "CRICKET",
    top: "top-[267px]",
    bgTop: "top-[264px]",
    bgLeft: "left-[89px]",
    bgWidth: "w-[155px]",
    bgHeight: "h-[33px]",
    textLeft: "left-[120px]",
    opacity: true,
  },
  {
    label: "FOOTBALL",
    top: "top-[344px]",
    bgTop: "top-[344px]",
    bgLeft: "left-[89px]",
    bgWidth: "w-[155px]",
    bgHeight: "h-8",
    textLeft: "left-28",
    opacity: false,
  },
  {
    label: "THROW BALL",
    top: "top-[426px]",
    bgTop: "top-[423px]",
    bgLeft: "left-[89px]",
    bgWidth: "w-[155px]",
    bgHeight: "h-8",
    textLeft: "left-[97px]",
    opacity: true,
  },
  {
    label: "VOLLEY BALL",
    top: "top-[506px]",
    bgTop: "top-[503px]",
    bgLeft: "left-24",
    bgWidth: "w-[148px]",
    bgHeight: "h-8",
    textLeft: "left-[102px]",
    opacity: true,
  },
];

export const Iphone = (): JSX.Element => {
  return (
    <div className="bg-[#ffffff80] w-full min-w-[393px] min-h-[852px] relative">
      <img
        className="absolute top-0 left-0 w-[393px] h-[852px] aspect-[0.67] object-cover"
        alt="Figma"
        src={figma21}
      />

      <div className="absolute top-36 left-[85px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        LIST OF EVENTS
      </div>

      <div
        className={`${events[0].bgTop} ${events[0].bgLeft} ${events[0].bgWidth} ${events[0].bgHeight} absolute bg-[#d9d9d9] opacity-50`}
      />
      <div className="absolute top-[267px] left-[120px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        CRICKET
      </div>

      <div
        className={`${events[1].bgTop} ${events[1].bgLeft} ${events[1].bgWidth} ${events[1].bgHeight} absolute bg-[#d9d9d9] opacity-50`}
      />
      <div className="absolute top-[344px] left-28 [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        FOOTBALL
      </div>

      <div
        className={`${events[2].bgTop} ${events[2].bgLeft} ${events[2].bgWidth} ${events[2].bgHeight} absolute bg-[#d9d9d9] opacity-50`}
      />
      <div className="absolute top-[426px] left-[97px] opacity-50 [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        THROW BALL
      </div>

      <div
        className={`${events[3].bgTop} ${events[3].bgLeft} ${events[3].bgWidth} ${events[3].bgHeight} absolute bg-[#d9d9d9] opacity-50`}
      />
      <div className="absolute top-[506px] left-[102px] w-[136px] opacity-50 [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        VOLLEY BALL
      </div>

      <div className="flex w-[121px] h-[51px] items-center justify-center gap-[var(--size-space-200)] pt-[var(--size-space-200)] pr-[var(--size-space-300)] pb-[var(--size-space-200)] pl-[var(--size-space-300)] absolute top-[582px] left-[101px] rounded-[var(--size-radius-200)]">
        <div className="relative w-fit font-single-line-body-base font-[number:var(--single-line-body-base-font-weight)] text-color-text-default-default text-[length:var(--single-line-body-base-font-size)] tracking-[var(--single-line-body-base-letter-spacing)] leading-[var(--single-line-body-base-line-height)] whitespace-nowrap [font-style:var(--single-line-body-base-font-style)]">
          Next
        </div>

        <ArrowRight className="!relative !w-4 !h-4" />
      </div>
    </div>
  );
};

PAGE 3
import { useState } from "react";
import figma31 from "./figma-3-1.png";

export const Iphone = (): JSX.Element => {
  const [formData, setFormData] = useState({
    name: "",
    age: "",
    department: "",
    event: "",
  });

  const handleChange = (e: React.ChangeEvent<HTMLInputElement>) => {
    const { name, value } = e.target;
    setFormData((prev) => ({ ...prev, [name]: value }));
  };

  const handleConfirm = () => {
    console.log("Form submitted:", formData);
  };

  return (
    <div className="bg-white w-full min-w-[393px] min-h-[852px] relative">
      <img
        className="absolute top-0 left-0 w-[393px] h-[852px] aspect-[0.56]"
        alt="Figma"
        src={figma31}
      />

      <div className="absolute top-32 left-[116px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        REGISTRATION
      </div>

      <div className="top-[233px] left-[110px] w-[165px] h-[41px] absolute bg-[#d9d9d9]">
        <input
          type="text"
          name="name"
          value={formData.name}
          onChange={handleChange}
          aria-label="Name"
          className="w-full h-full bg-transparent px-2 [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-base tracking-[0] leading-[normal] outline-none border-none"
        />
      </div>

      <div className="top-[347px] left-[110px] w-[165px] h-[37px] absolute bg-[#d9d9d9]">
        <input
          type="text"
          name="age"
          value={formData.age}
          onChange={handleChange}
          aria-label="Age"
          className="w-full h-full bg-transparent px-2 [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-base tracking-[0] leading-[normal] outline-none border-none"
        />
      </div>

      <div className="top-[441px] left-[184px] w-[165px] h-[42px] absolute bg-[#d9d9d9]">
        <input
          type="text"
          name="department"
          value={formData.department}
          onChange={handleChange}
          aria-label="Department"
          className="w-full h-full bg-transparent px-2 [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-base tracking-[0] leading-[normal] outline-none border-none"
        />
      </div>

      <div className="absolute top-[239px] left-[31px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        NAME
      </div>

      <div className="absolute top-[354px] left-[42px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        AGE
      </div>

      <div className="absolute top-[447px] left-[11px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        DEPARTMENT
      </div>

      <div className="top-[540px] left-[110px] w-[157px] h-[37px] absolute bg-[#d9d9d9]">
        <input
          type="text"
          name="event"
          value={formData.event}
          onChange={handleChange}
          aria-label="Event"
          className="w-full h-full bg-transparent px-2 [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-base tracking-[0] leading-[normal] outline-none border-none"
        />
      </div>

      <div className="absolute top-[544px] left-[31px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        EVENT
      </div>

      <button
        onClick={handleConfirm}
        className="top-[680px] left-[117px] w-[158px] h-[60px] absolute bg-[#d9d9d9] cursor-pointer flex items-center justify-center"
        aria-label="Confirm registration"
        type="button"
      >
        <span className="[font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
          CONFIRM
        </span>
      </button>
    </div>
  );
};

PAGE 4
import messi1 from "./messi-1.png";

export const Iphone = (): JSX.Element => {
  return (
    <div className="bg-white overflow-hidden w-full min-w-[393px] min-h-[852px] relative">
      <img
        className="absolute top-0 left-0 w-[393px] h-[852px] aspect-[0.46] object-cover"
        alt="Messi"
        src={messi1}
      />

      <div className="absolute top-[162px] left-[38px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        THANK YOU FOR REGISTERING
      </div>

      <div className="absolute top-[278px] left-[97px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        HAVE A GOOD DAY
      </div>

      <div className="absolute top-[784px] left-[225px] w-[168px] [font-family:'Racing_Sans_One-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        MANORAJAPRIYAN.L.E
      </div>
    </div>
  );
};

```



## OUTPUT:
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
