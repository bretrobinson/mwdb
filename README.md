# mwdb
Movie Warning Database

Need to set ENVs:

TMDB_API_KEY -> needs to be put in toutes/api-key.js or set this env
  api-key.js:
    const apiKey = 'api-key-from-tmdb';
    module.exports.apiKey = apiKey;

DATABASE_URL -> either local or an Atlas string

PORT -> default is 8000 iif not set
