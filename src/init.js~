

import SOURCE_IMPORTS from './source.js';

export default function init () {
  if (typeof SOURCE_IMPORTS !== 'object') {
    throw new Error('SOURCE_IMPORTS IS NOT AN OBJECT');
  }
  return Object.keys(SOURCE_IMPORTS).map( (sourceFunction) => sourceFunction.init() );
}
