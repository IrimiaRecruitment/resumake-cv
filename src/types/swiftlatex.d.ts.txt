declare module 'swiftlatex' {
  export const PdfTeXEngine: any;
  export const XeTeXEngine: any;
  export const DvipdfmxEngine: any;

  export interface LaTeXOpts {
    [key: string]: any;
  }
}
